# Lab Report 2 - Servers and Bugs
## Part1: String Server
## Part2
My code for StringServer:
```
class Handler implements URLHandler {
    // The one bit of state on the server: a number that will be manipulated by
    // various requests.
    ArrayList<String> str = new ArrayList<>();

    public String handleRequest(URI url) {

        if (url.getPath().equals("/")) {
            String output = "";
            if(str == null){
                return "There is no current string";
            }
            \\adding new line
            for(String curString: str){
                output = output + curString + "\n";
            }
            return "current string is "+ output;
            
        } 
        else if (url.getPath().contains("/add")) {
            String output = "";
            String[] parameters = url.getQuery().split("=");
            if (parameters[0].equals("s")) {
                str.add(parameters[1]);
                //adding new line
                for(String curString: str){
                    output = output + curString + "\n";
                }
                return output;
            
            } 
        }
        return "404 Not Found!";
    }
}
```
The output for `/add-message` :
![image](StringServerHello.png)
The method `handleRequest(URI url)` is being called in this case, more specifically, it is using the else statement to add a string into the server.
## Part3
