# Lab Report3 - Researching Commands
## Command: grep -c
Example1:
```
xinyihu@XinyideMacBook-Air docsearch-main % grep -c "vista" written_2/travel_guides/berlitz1/*.txt
written_2/travel_guides/berlitz1/HandRHawaii.txt:0
written_2/travel_guides/berlitz1/HandRHongKong.txt:0
written_2/travel_guides/berlitz1/HandRIbiza.txt:0
written_2/travel_guides/berlitz1/HandRIsrael.txt:0
written_2/travel_guides/berlitz1/HandRIstanbul.txt:0
written_2/travel_guides/berlitz1/HandRJamaica.txt:0
written_2/travel_guides/berlitz1/HandRJerusalem.txt:0
written_2/travel_guides/berlitz1/HandRLakeDistrict.txt:0
written_2/travel_guides/berlitz1/HandRLasVegas.txt:0
written_2/travel_guides/berlitz1/HandRLisbon.txt:0
written_2/travel_guides/berlitz1/HandRLosAngeles.txt:0
written_2/travel_guides/berlitz1/HandRMadeira.txt:0
written_2/travel_guides/berlitz1/HandRMadrid.txt:0
written_2/travel_guides/berlitz1/HandRMallorca.txt:0
written_2/travel_guides/berlitz1/HistoryDublin.txt:0
written_2/travel_guides/berlitz1/HistoryEdinburgh.txt:0
written_2/travel_guides/berlitz1/HistoryEgypt.txt:0
written_2/travel_guides/berlitz1/HistoryFWI.txt:0
written_2/travel_guides/berlitz1/HistoryFrance.txt:0
written_2/travel_guides/berlitz1/HistoryGreek.txt:0
written_2/travel_guides/berlitz1/HistoryHawaii.txt:0
written_2/travel_guides/berlitz1/HistoryHongKong.txt:0
written_2/travel_guides/berlitz1/HistoryIbiza.txt:0
written_2/travel_guides/berlitz1/HistoryIndia.txt:0
written_2/travel_guides/berlitz1/HistoryIsrael.txt:0
written_2/travel_guides/berlitz1/HistoryIstanbul.txt:0
written_2/travel_guides/berlitz1/HistoryItaly.txt:0
written_2/travel_guides/berlitz1/HistoryJamaica.txt:0
written_2/travel_guides/berlitz1/HistoryJapan.txt:0
written_2/travel_guides/berlitz1/HistoryJerusalem.txt:0
written_2/travel_guides/berlitz1/HistoryLakeDistrict.txt:0
written_2/travel_guides/berlitz1/HistoryLasVegas.txt:0
written_2/travel_guides/berlitz1/HistoryMadeira.txt:0
written_2/travel_guides/berlitz1/HistoryMadrid.txt:0
written_2/travel_guides/berlitz1/HistoryMalaysia.txt:0
written_2/travel_guides/berlitz1/HistoryMallorca.txt:0
written_2/travel_guides/berlitz1/IntroDublin.txt:1
written_2/travel_guides/berlitz1/IntroEdinburgh.txt:0
written_2/travel_guides/berlitz1/IntroEgypt.txt:0
written_2/travel_guides/berlitz1/IntroFWI.txt:0
written_2/travel_guides/berlitz1/IntroFrance.txt:0
written_2/travel_guides/berlitz1/IntroGreek.txt:0
written_2/travel_guides/berlitz1/IntroHongKong.txt:0
written_2/travel_guides/berlitz1/IntroIbiza.txt:0
written_2/travel_guides/berlitz1/IntroIndia.txt:0
written_2/travel_guides/berlitz1/IntroIsrael.txt:0
written_2/travel_guides/berlitz1/IntroIstanbul.txt:0
written_2/travel_guides/berlitz1/IntroItaly.txt:0
written_2/travel_guides/berlitz1/IntroJamaica.txt:0
written_2/travel_guides/berlitz1/IntroJapan.txt:0
written_2/travel_guides/berlitz1/IntroJerusalem.txt:0
written_2/travel_guides/berlitz1/IntroLakeDistrict.txt:1
written_2/travel_guides/berlitz1/IntroLasVegas.txt:0
written_2/travel_guides/berlitz1/IntroLosAngeles.txt:0
written_2/travel_guides/berlitz1/IntroMadeira.txt:1
written_2/travel_guides/berlitz1/IntroMadrid.txt:0
written_2/travel_guides/berlitz1/IntroMalaysia.txt:0
written_2/travel_guides/berlitz1/IntroMallorca.txt:0
written_2/travel_guides/berlitz1/JungleMalaysia.txt:0
written_2/travel_guides/berlitz1/WhatToDublin.txt:0
written_2/travel_guides/berlitz1/WhatToEdinburgh.txt:0
written_2/travel_guides/berlitz1/WhatToEgypt.txt:0
written_2/travel_guides/berlitz1/WhatToFWI.txt:0
written_2/travel_guides/berlitz1/WhatToFrance.txt:0
written_2/travel_guides/berlitz1/WhatToGreek.txt:0
written_2/travel_guides/berlitz1/WhatToHawaii.txt:0
written_2/travel_guides/berlitz1/WhatToHongKong.txt:0
written_2/travel_guides/berlitz1/WhatToIbiza.txt:0
written_2/travel_guides/berlitz1/WhatToIndia.txt:0
written_2/travel_guides/berlitz1/WhatToIsrael.txt:0
written_2/travel_guides/berlitz1/WhatToIstanbul.txt:0
written_2/travel_guides/berlitz1/WhatToItaly.txt:0
written_2/travel_guides/berlitz1/WhatToJamaica.txt:0
written_2/travel_guides/berlitz1/WhatToJapan.txt:0
written_2/travel_guides/berlitz1/WhatToLakeDistrict.txt:0
written_2/travel_guides/berlitz1/WhatToLasVegas.txt:0
written_2/travel_guides/berlitz1/WhatToLosAngeles.txt:0
written_2/travel_guides/berlitz1/WhatToMadeira.txt:0
written_2/travel_guides/berlitz1/WhatToMalaysia.txt:0
written_2/travel_guides/berlitz1/WhatToMallorca.txt:0
written_2/travel_guides/berlitz1/WhereToDublin.txt:0
written_2/travel_guides/berlitz1/WhereToEdinburgh.txt:0
written_2/travel_guides/berlitz1/WhereToEgypt.txt:0
written_2/travel_guides/berlitz1/WhereToFWI.txt:0
written_2/travel_guides/berlitz1/WhereToFrance.txt:3
written_2/travel_guides/berlitz1/WhereToGreek.txt:1
written_2/travel_guides/berlitz1/WhereToHawaii.txt:0
written_2/travel_guides/berlitz1/WhereToHongKong.txt:0
written_2/travel_guides/berlitz1/WhereToIbiza.txt:2
written_2/travel_guides/berlitz1/WhereToIndia.txt:0
written_2/travel_guides/berlitz1/WhereToIsrael.txt:1
written_2/travel_guides/berlitz1/WhereToIstanbul.txt:0
written_2/travel_guides/berlitz1/WhereToItaly.txt:0
written_2/travel_guides/berlitz1/WhereToJapan.txt:0
written_2/travel_guides/berlitz1/WhereToJerusalem.txt:3
written_2/travel_guides/berlitz1/WhereToLakeDistrict.txt:2
written_2/travel_guides/berlitz1/WhereToLosAngeles.txt:0
written_2/travel_guides/berlitz1/WhereToMadeira.txt:1
written_2/travel_guides/berlitz1/WhereToMadrid.txt:0
written_2/travel_guides/berlitz1/WhereToMalaysia.txt:0
written_2/travel_guides/berlitz1/WhereToMallorca.txt:0
```
This grep -c command return the number of times a keyword appears in txt files, in this case I search for the word "vista", the number at the end of each path is the number it appears in the previous txt file, for example, "vista" occurs 3 times in the file "WhereToJerusalem.txt".

### Example 2:
```
grep -c good travel_guides/berlitz1/*.txt
```
Result:
```
travel_guides/berlitz1/HandRHawaii.txt:0
travel_guides/berlitz1/HandRHongKong.txt:0
travel_guides/berlitz1/HandRIbiza.txt:0
travel_guides/berlitz1/HandRIsrael.txt:12
travel_guides/berlitz1/HandRIstanbul.txt:0
travel_guides/berlitz1/HandRJamaica.txt:3
travel_guides/berlitz1/HandRJerusalem.txt:0
travel_guides/berlitz1/HandRLakeDistrict.txt:0
travel_guides/berlitz1/HandRLasVegas.txt:0
travel_guides/berlitz1/HandRLisbon.txt:0
travel_guides/berlitz1/HandRLosAngeles.txt:0
travel_guides/berlitz1/HandRMadeira.txt:0
travel_guides/berlitz1/HandRMadrid.txt:1
travel_guides/berlitz1/HandRMallorca.txt:0
travel_guides/berlitz1/HistoryDublin.txt:1
travel_guides/berlitz1/HistoryEdinburgh.txt:0
travel_guides/berlitz1/HistoryEgypt.txt:0
travel_guides/berlitz1/HistoryFWI.txt:1
travel_guides/berlitz1/HistoryFrance.txt:1
travel_guides/berlitz1/HistoryGreek.txt:0
travel_guides/berlitz1/HistoryHawaii.txt:1
travel_guides/berlitz1/HistoryHongKong.txt:3
travel_guides/berlitz1/HistoryIbiza.txt:0
travel_guides/berlitz1/HistoryIndia.txt:5
travel_guides/berlitz1/HistoryIsrael.txt:0
travel_guides/berlitz1/HistoryIstanbul.txt:2
travel_guides/berlitz1/HistoryItaly.txt:2
travel_guides/berlitz1/HistoryJamaica.txt:0
travel_guides/berlitz1/HistoryJapan.txt:4
travel_guides/berlitz1/HistoryJerusalem.txt:0
travel_guides/berlitz1/HistoryLakeDistrict.txt:4
travel_guides/berlitz1/HistoryLasVegas.txt:1
travel_guides/berlitz1/HistoryMadeira.txt:0
travel_guides/berlitz1/HistoryMadrid.txt:1
travel_guides/berlitz1/HistoryMalaysia.txt:1
travel_guides/berlitz1/HistoryMallorca.txt:0
travel_guides/berlitz1/IntroDublin.txt:3
travel_guides/berlitz1/IntroEdinburgh.txt:0
travel_guides/berlitz1/IntroEgypt.txt:1
travel_guides/berlitz1/IntroFWI.txt:0
travel_guides/berlitz1/IntroFrance.txt:1
travel_guides/berlitz1/IntroGreek.txt:1
travel_guides/berlitz1/IntroHongKong.txt:0
travel_guides/berlitz1/IntroIbiza.txt:0
travel_guides/berlitz1/IntroIndia.txt:6
travel_guides/berlitz1/IntroIsrael.txt:0
travel_guides/berlitz1/IntroIstanbul.txt:0
travel_guides/berlitz1/IntroItaly.txt:1
travel_guides/berlitz1/IntroJamaica.txt:3
travel_guides/berlitz1/IntroJapan.txt:1
travel_guides/berlitz1/IntroJerusalem.txt:0
travel_guides/berlitz1/IntroLakeDistrict.txt:2
travel_guides/berlitz1/IntroLasVegas.txt:1
travel_guides/berlitz1/IntroLosAngeles.txt:1
travel_guides/berlitz1/IntroMadeira.txt:0
travel_guides/berlitz1/IntroMadrid.txt:0
travel_guides/berlitz1/IntroMalaysia.txt:2
travel_guides/berlitz1/IntroMallorca.txt:0
travel_guides/berlitz1/JungleMalaysia.txt:0
travel_guides/berlitz1/WhatToDublin.txt:8
travel_guides/berlitz1/WhatToEdinburgh.txt:4
travel_guides/berlitz1/WhatToEgypt.txt:8
travel_guides/berlitz1/WhatToFWI.txt:2
travel_guides/berlitz1/WhatToFrance.txt:0
travel_guides/berlitz1/WhatToGreek.txt:3
travel_guides/berlitz1/WhatToHawaii.txt:0
travel_guides/berlitz1/WhatToHongKong.txt:12
travel_guides/berlitz1/WhatToIbiza.txt:10
travel_guides/berlitz1/WhatToIndia.txt:6
travel_guides/berlitz1/WhatToIsrael.txt:14
travel_guides/berlitz1/WhatToIstanbul.txt:11
travel_guides/berlitz1/WhatToItaly.txt:17
travel_guides/berlitz1/WhatToJamaica.txt:11
travel_guides/berlitz1/WhatToJapan.txt:18
travel_guides/berlitz1/WhatToLakeDistrict.txt:9
travel_guides/berlitz1/WhatToLasVegas.txt:3
travel_guides/berlitz1/WhatToLosAngeles.txt:3
travel_guides/berlitz1/WhatToMadeira.txt:12
travel_guides/berlitz1/WhatToMalaysia.txt:6
travel_guides/berlitz1/WhatToMallorca.txt:5
travel_guides/berlitz1/WhereToDublin.txt:8
travel_guides/berlitz1/WhereToEdinburgh.txt:3
travel_guides/berlitz1/WhereToEgypt.txt:7
travel_guides/berlitz1/WhereToFWI.txt:7
travel_guides/berlitz1/WhereToFrance.txt:49
travel_guides/berlitz1/WhereToGreek.txt:6
travel_guides/berlitz1/WhereToHawaii.txt:0
travel_guides/berlitz1/WhereToHongKong.txt:10
travel_guides/berlitz1/WhereToIbiza.txt:5
travel_guides/berlitz1/WhereToIndia.txt:13
travel_guides/berlitz1/WhereToIsrael.txt:13
travel_guides/berlitz1/WhereToIstanbul.txt:5
travel_guides/berlitz1/WhereToItaly.txt:17
travel_guides/berlitz1/WhereToJapan.txt:19
travel_guides/berlitz1/WhereToJerusalem.txt:7
travel_guides/berlitz1/WhereToLakeDistrict.txt:15
travel_guides/berlitz1/WhereToLosAngeles.txt:7
travel_guides/berlitz1/WhereToMadeira.txt:12
travel_guides/berlitz1/WhereToMadrid.txt:0
travel_guides/berlitz1/WhereToMalaysia.txt:36
travel_guides/berlitz1/WhereToMallorca.txt:9
```
In this example I search for the word "good", it can become a aspect to evaluate and decide where you want to travel based on the frequency that place being praise.

## Command 2: grep -r -l
### Example 1:
```
grep -r -l vista travel_guides
```
Result:
```
travel_guides/berlitz1/IntroDublin.txt
travel_guides/berlitz1/IntroMadeira.txt
travel_guides/berlitz1/WhereToGreek.txt
travel_guides/berlitz1/WhereToLakeDistrict.txt
travel_guides/berlitz1/WhereToIsrael.txt
travel_guides/berlitz1/WhereToFrance.txt
travel_guides/berlitz1/WhereToMadeira.txt
travel_guides/berlitz1/WhereToIbiza.txt
travel_guides/berlitz1/WhereToJerusalem.txt
travel_guides/berlitz1/IntroLakeDistrict.txt
travel_guides/berlitz2/Costa-WhereToGo.txt
travel_guides/berlitz2/Portugal-WhereToGo.txt
travel_guides/berlitz2/Bahamas-WhereToGo.txt
travel_guides/berlitz2/Crete-WhereToGo.txt
travel_guides/berlitz2/Athens-WhereToGo.txt
travel_guides/berlitz2/China-WhereToGo.txt
travel_guides/berlitz2/CstaBlanca-WhereToGo.txt
travel_guides/berlitz2/CanaryIslands-WhereToGo.txt
travel_guides/berlitz2/Nepal-WhatToDo.txt
travel_guides/berlitz2/Vallarta-WhereToGo.txt
```
Command `grep -r` will search recursively, examining each file in the provided directory. `grep -l` returns only the names of files containing a valid match. In this case
 `grep -r` recursively search for the key word "vista" and listed the name and the contexts that include "vista". When we add `-l` after it, the terminal only give us the name of the files contain "vista" but not showing the context anymore.
 
### Example 3:
```
grep -r -l delicious travel_guides
```
Results:
```
travel_guides/berlitz1/WhatToLakeDistrict.txt
travel_guides/berlitz1/WhereToGreek.txt
travel_guides/berlitz1/WhatToIbiza.txt
travel_guides/berlitz1/WhatToMadeira.txt
travel_guides/berlitz1/WhereToMalaysia.txt
travel_guides/berlitz1/WhereToFrance.txt
travel_guides/berlitz1/IntroFWI.txt
travel_guides/berlitz1/HandRIsrael.txt
travel_guides/berlitz1/WhatToGreek.txt
travel_guides/berlitz1/WhereToLosAngeles.txt
travel_guides/berlitz1/WhereToHongKong.txt
travel_guides/berlitz1/WhereToFWI.txt
travel_guides/berlitz1/WhatToIstanbul.txt
travel_guides/berlitz1/WhatToLosAngeles.txt
travel_guides/berlitz2/CostaBlanca-WhatToDo.txt
travel_guides/berlitz2/Portugal-WhereToGo.txt
travel_guides/berlitz2/Bahamas-WhereToGo.txt
travel_guides/berlitz2/Crete-WhereToGo.txt
travel_guides/berlitz2/Canada-WhereToGo.txt
travel_guides/berlitz2/China-WhereToGo.txt
travel_guides/berlitz2/CstaBlanca-WhereToGo.txt
travel_guides/berlitz2/Cuba-WhereToGo.txt
travel_guides/berlitz2/CanaryIslands-WhereToGo.txt
travel_guides/berlitz2/Algarve-WhereToGo.txt
travel_guides/berlitz2/Athens-Intro.txt
```
This command search for the word "delicious" in all the files in travel_guildes, and returns the files' name that contian "delicious" in it's context. This can be helpful, it is kind of similar to online searchin when you want wan to target something like "food", "mountian", etc.
## Command 3: grep -n
## Example 1:
```
grep -r -n weather travel_guides/berlitz1/
```
Result:
```
travel_guides/berlitz1//IntroFrance.txt:67:        shoreline has earned the region a reputation for rough weather. In fact
travel_guides/berlitz1//IntroFrance.txt:89:        the ravages of time, weather, war, revolution, and urban development.
travel_guides/berlitz1//IntroMadeira.txt:38:        year-round sub-tropical spring weather with a southerly breeze and
travel_guides/berlitz1//WhatToLakeDistrict.txt:273:        weather is fine — are trips to see the animals at Trotters and Friends
travel_guides/berlitz1//WhatToLakeDistrict.txt:276:        trip on a lake ferry can be run in any sort of weather.
travel_guides/berlitz1//WhatToLakeDistrict.txt:309:        vice versa). Many outside beer gardens — very popular when the weather
travel_guides/berlitz1//WhereToGreek.txt:62:        extremely enjoyable activities, because the weather is pleasant but not
travel_guides/berlitz1//WhereToLakeDistrict.txt:284:        aquarium, interesting whatever the weather but certainly a good place
travel_guides/berlitz1//WhereToLakeDistrict.txt:467:        in the Lakes. No matter what the weather is like, the landscape is
travel_guides/berlitz1//WhereToLakeDistrict.txt:914:        falls make will depend to a certain extent on what kind of weather the
travel_guides/berlitz1//WhereToLakeDistrict.txt:916:        torrent, but in dry weather the flow can slow to a mere trickle. Park
travel_guides/berlitz1//WhereToLakeDistrict.txt:1009:        also tractor rides, weather permitting. With a café and picnic area,
travel_guides/berlitz1//WhatToIbiza.txt:544:        be sipped before or after meals. In hot weather, the locals drink it
travel_guides/berlitz1//WhereToIndia.txt:595:        Governor’s Residence, you can see huge slabs of concrete like weathered
travel_guides/berlitz1//WhereToIndia.txt:914:        sometimes ferocious weather of India and Mahmud of Ghazni’s
travel_guides/berlitz1//WhereToItaly.txt:1638:        A time-locked city of rich russet browns and weathered
travel_guides/berlitz1//WhereToItaly.txt:1748:        warm-weather months, stop off at the fashionable seaside resorts on
travel_guides/berlitz1//WhereToItaly.txt:1952:        warm-weather months an open funivia brings you up to the basilica of
travel_guides/berlitz1//WhereToItaly.txt:2084:        warm weather months, their spirited 4-piece orchestras play everything
travel_guides/berlitz1//WhereToItaly.txt:2146:        lighthouse, weather vane, and gun turret. Emperor Frederick III rode
travel_guides/berlitz1//WhereToItaly.txt:2457:        Venice’s weather and heavy humidity can sap the most energetic of
travel_guides/berlitz1//WhereToItaly.txt:3307:        weather. The Aosta Valley’s Courmayeur is as pleasant a base for
travel_guides/berlitz1//WhereToItaly.txt:3898:        outdoor classical concerts that take place during warm weather months.
travel_guides/berlitz1//WhatToMadeira.txt:78:        many shops in the mountains. Unexpectedly chilly weather might make
travel_guides/berlitz1//WhatToMadeira.txt:309:        the weather, for Santo da Serra has a wet micro-climate and
travel_guides/berlitz1//WhatToMadeira.txt:310:        fair-weather golf is relatively limited outside of summer. Green fees
travel_guides/berlitz1//WhereToJapan.txt:834:        “out of season” (especially in wet weather) is not recommended, but
travel_guides/berlitz1//WhereToJapan.txt:862:        shore, where — with luck and good weather — you get a perfect
travel_guides/berlitz1//WhereToEdinburgh.txt:241:        The experience is best when the weather is bright. There is a viewing
travel_guides/berlitz1//WhereToEdinburgh.txt:526:        weathering and pollution. A small stone tomb in the southeast corner
travel_guides/berlitz1//WhereToEdinburgh.txt:566:        to watch exciting weather phenomena flashing above.
travel_guides/berlitz1//WhereToFrance.txt:10:        weather important? Do you want to lie on beaches or hike in mountains?
travel_guides/berlitz1//WhereToFrance.txt:1878:        The Atlantic climate produces changeable but pleasant summer weather.
travel_guides/berlitz1//WhereToFrance.txt:2031:        ­weather-beaten old hotels give a nostalgic peek at Napoleon III’s
travel_guides/berlitz1//WhereToFrance.txt:2957:        people-watching. Good weather, with hot days and balmy nights, is
travel_guides/berlitz1//WhereToMallorca.txt:304:        seem to have been fairly miserable: Chopin was unwell, the weather was
travel_guides/berlitz1//WhatToMallorca.txt:226:        The Balearics’ fine sandy beaches and sunny weather make
travel_guides/berlitz1//WhereToMadeira.txt:492:        south coasts of the island. In good weather, hikers are drawn to its
travel_guides/berlitz1//WhereToMadeira.txt:513:        isn’t really a place to linger, unless the weather’s warm and you want
travel_guides/berlitz1//WhereToMadeira.txt:587:        and south makes weather forecasting a difficult proposition on Madeira.
travel_guides/berlitz1//WhereToMadeira.txt:627:        hazardous, with landslides removing parts of the path. Check weather
travel_guides/berlitz1//WhereToMadeira.txt:692:        lovely spot for a picnic, although if the weather is clear you might
travel_guides/berlitz1//WhereToMadeira.txt:906:        Sandstone cliffs and rocks have been weathered into interesting shapes
travel_guides/berlitz1//WhereToLosAngeles.txt:794:        balmy weather and luscious orange groves, Midwesterners flocked here in
travel_guides/berlitz1//HistoryEdinburgh.txt:231:        bad weather. Another campaign was held in 1715 under the Jacobite Earl
travel_guides/berlitz1//HistoryLakeDistrict.txt:12:        weather patterns, settlers used the clearings in the lowlands for
travel_guides/berlitz1//IntroLakeDistrict.txt:144:        prepared to experience some inclement weather during your visit. The
travel_guides/berlitz1//IntroLakeDistrict.txt:148:        retains its beauty in all types of weather, and in all seasons. Spring
travel_guides/berlitz1//WhereToFWI.txt:63:        Today, weathered banana schooners chug past yachts and
travel_guides/berlitz1//WhereToFWI.txt:717:        village with more than its share of friendly, weatherbeaten people.
travel_guides/berlitz1//WhatToLosAngeles.txt:152:        With exceptional year-round weather, over 72 miles (116 km)
```
In this example, I recursively search through the files in `travel_guides/berlitz1/`, finding the keyword "weather" and use the command `-n` to return the line number that "weather" occurs.
### Example 2:
```
grep -r -n performance  travel_guides/berlitz1/
```
Result:
```
travel_guides/berlitz1//IntroEdinburgh.txt:108:        arts event in the world, with hundreds of performances in numerous
travel_guides/berlitz1//IntroEdinburgh.txt:117:        performances ranging from the avant-garde to the downright irreverent.
travel_guides/berlitz1//IntroDublin.txt:67:        seeing a performance at the Abbey Theatre or Gate Theatre. The city’s
travel_guides/berlitz1//WhatToLakeDistrict.txt:287:        the summer, but many performances can be fully booked months ahead. The
travel_guides/berlitz1//WhereToGreek.txt:625:        Roman Odeon or theater, used in summer for performances. Nearby is Casa
travel_guides/berlitz1//WhereToLakeDistrict.txt:56:        the theater housed here offers a program of performances throughout the
travel_guides/berlitz1//WhereToLakeDistrict.txt:270:        Theatre in the Forest holds concerts and performances on weekends in
travel_guides/berlitz1//WhereToLakeDistrict.txt:382:        offers classes, exhibitions, and performances, along with restaurants
travel_guides/berlitz1//WhereToLakeDistrict.txt:443:        open-air performances are held on the estate, and a commercial gallery
travel_guides/berlitz1//WhereToLakeDistrict.txt:814:        performances ranging from drama to Gilbert and Sullivan to English
travel_guides/berlitz1//WhatToIbiza.txt:243:        one-time performances in other towns and villages during fiestas,
travel_guides/berlitz1//WhereToItaly.txt:431:        camels, and endless cast. Rumors persist that the performances will
travel_guides/berlitz1//WhereToItaly.txt:1418:        performances. In the middle of the nearby Pond of Neptune (Vasca del
travel_guides/berlitz1//WhereToItaly.txt:2909:        performance there or at least visit the little museum (left of the
travel_guides/berlitz1//HistoryLasVegas.txt:170:        financed the operation were displeased with its performance; Siegel was
travel_guides/berlitz1//WhatToFWI.txt:311:        dance performance are you likely to see rose, a slave woman’s washing
travel_guides/berlitz1//WhatToFWI.txt:356:        “black magic” performances staged for tourists.
travel_guides/berlitz1//WhereToMalaysia.txt:1349:        on Jalan Mahmood opposite the Perdana Hotel, with performances that
travel_guides/berlitz1//WhereToMalaysia.txt:1908:        craft demonstrations and cultural performances. Described as a “Living
travel_guides/berlitz1//WhereToMalaysia.txt:1974:        cultural performances soon after arrival for day-trippers or at the
travel_guides/berlitz1//WhereToMalaysia.txt:1979:        rice, and a welcome dance. The musical and cultural performance
travel_guides/berlitz1//WhatToDublin.txt:193:        program of dance, drama, and performance arts. Both the Andrews Lane
travel_guides/berlitz1//WhatToDublin.txt:216:        enterprising Opera Theatre Company does two or three performances a
travel_guides/berlitz1//WhatToDublin.txt:292:        readings, and performances, all geared toward youngsters. It’s best to
travel_guides/berlitz1//WhereToJapan.txt:997:        dignitaries would sit while enjoying dance performances and music
travel_guides/berlitz1//WhereToJapan.txt:1661:        Bunraku is a Japanese performance art of surprising
travel_guides/berlitz1//WhereToJapan.txt:1669:        Theater (at the bottom of Midosuji Boulevard) gives kabuki performances
travel_guides/berlitz1//WhereToEgypt.txt:185:        performances of the Whirling Dervishes (who achieve religious ecstasy
travel_guides/berlitz1//WhereToEdinburgh.txt:199:        arena erected for performances of the Military Tattoo.
travel_guides/berlitz1//WhereToEdinburgh.txt:364:        Playhouse Close was the site of a theater where performances resulted
travel_guides/berlitz1//WhatToIsrael.txt:221:        p.m. and one hour before performances.
travel_guides/berlitz1//WhatToIsrael.txt:254:        puts on English-language performances.
travel_guides/berlitz1//WhereToFrance.txt:1110:        retrospective son et lumière performance in the Citadelle, parts of
travel_guides/berlitz1//WhereToFrance.txt:2654:        important Roman amphitheaters that are still used for performances
travel_guides/berlitz1//WhereToDublin.txt:285:        avant-garde in painting and sculpture; it has a performance space
travel_guides/berlitz1//WhereToDublin.txt:379:        plaque commemorates the first performance of Handel’s Messiah, which
travel_guides/berlitz1//WhereToDublin.txt:967:        sculpture. It also has a performance space for dance, drama, and other
travel_guides/berlitz1//WhatToEdinburgh.txt:25:        the dozens of performances and events in the many theaters of the city
travel_guides/berlitz1//WhatToEdinburgh.txt:36:        of extra performances held in the city. Initially the Fringe consisted
travel_guides/berlitz1//WhatToEdinburgh.txt:38:        official festival program but nevertheless decided to hold performances
travel_guides/berlitz1//WhatToEdinburgh.txt:44:        of performances taking place daily (at all times of the day and night).
travel_guides/berlitz1//WhatToEdinburgh.txt:53:        Fringe performances, while a daily program is published during the
travel_guides/berlitz1//WhatToEdinburgh.txt:78:        summer festivals to see performances of the arts. The city is home to
travel_guides/berlitz1//WhatToEdinburgh.txt:82:        performances as well as popular shows featuring international bands and
travel_guides/berlitz1//WhatToEdinburgh.txt:319:        Festival holds arts, theater, and dance activities and performances
travel_guides/berlitz1//WhatToGreek.txt:204:        traditional Greek dances and musical performances, as well as clubs
travel_guides/berlitz1//WhatToGreek.txt:233:        It is becoming more difficult to see performances on the
travel_guides/berlitz1//WhatToGreek.txt:235:        at a private wedding or feast day when the performances are set in
travel_guides/berlitz1//WhatToGreek.txt:244:        find an English copy of the plot before the performance begins. When
travel_guides/berlitz1//HistoryMalaysia.txt:371:        up by new high-performance fighter planes.
travel_guides/berlitz1//WhatToIndia.txt:104:        silences. A fully realized performance could go on for two or three
travel_guides/berlitz1//WhereToLosAngeles.txt:48:        up for the city’s encore performance.
travel_guides/berlitz1//WhereToLosAngeles.txt:436:        Monica Museum of Art, which showcases the avant-garde and performance
travel_guides/berlitz1//WhereToLosAngeles.txt:1032:        performance venues.
travel_guides/berlitz1//WhereToLosAngeles.txt:1067:        music, and opera performances by visiting international and local
travel_guides/berlitz1//WhatToItaly.txt:100:        Palermo also have fine regional houses. These show performances from
travel_guides/berlitz1//WhatToItaly.txt:103:        Verona’s ancient Roman Arena, a unique location for performances of
travel_guides/berlitz1//WhatToItaly.txt:105:        Baths of Caracalla still offer the occasional performance — though
travel_guides/berlitz1//WhereToJerusalem.txt:701:        return in the evening for an Arab dinner and a performance of local
travel_guides/berlitz1//WhatToJapan.txt:142:        performances, aided by stunning costumes and elaborate make-up and
travel_guides/berlitz1//WhatToJapan.txt:168:        aficionados, a noh performance is an eclectic nirvana. For many others,
travel_guides/berlitz1//WhatToJapan.txt:177:        Ever since the Tokugawa shoguns restricted performances to
travel_guides/berlitz1//WhatToJapan.txt:199:        lascivious performances. With the audience’s passionate loyalties to
travel_guides/berlitz1//WhatToJapan.txt:210:        the performance, providing simultaneous English-language translation of
travel_guides/berlitz1//WhatToJapan.txt:218:        performances are also put on several weeks each year at Tokyo’s
travel_guides/berlitz1//WhatToJamaica.txt:450:        the season there are many exhibitions and performances in the gardens
travel_guides/berlitz1//WhatToHongKong.txt:223:        Other performance centers are the City Hall cultural complex, with
travel_guides/berlitz1//WhatToHongKong.txt:226:        for dance, drama, and concert performances; and the Hong Kong Arts
travel_guides/berlitz1//WhatToHongKong.txt:252:        Cantonese; there are English-language performances at the Fringe Club
travel_guides/berlitz1//WhereToHongKong.txt:980:        and dance performances.
travel_guides/berlitz1//WhereToFWI.txt:118:        performances, there’s a fine view across the bay to Basse-Terre.
travel_guides/berlitz1//WhatToIstanbul.txt:178:        the next performance in English.
travel_guides/berlitz1//WhereToIstanbul.txt:1160:        people, and still accommodates the crowds who gather for performances
travel_guides/berlitz1//IntroJapan.txt:261:        arrangements; struggle to stay awake through an entire noh performance.
travel_guides/berlitz1//WhatToLasVegas.txt:252:        unique Las Vegas experience that borders on performance art. This
travel_guides/berlitz1//WhatToLasVegas.txt:301:        yesterday and today. Impersonators render uncanny performances of the
travel_guides/berlitz1//WhatToLasVegas.txt:712:        and theater performances. Activity information is available through the
travel_guides/berlitz1//WhatToLosAngeles.txt:241:        world-class opera and symphony performances, comedy clubs, Broadway
travel_guides/berlitz1//WhatToLosAngeles.txt:257:        finest music and drama performances in the country. The city’s premier
travel_guides/berlitz1//WhatToLosAngeles.txt:270:        all year round on the three outdoor performance stages of the
travel_guides/berlitz1//WhatToLosAngeles.txt:277:        performance with Angelenos toting gourmet picnic baskets and fine wine.
```
In this example, I search for "performance" instead. This command can help you to locat the information you want by searching the key word, you can find the original text by looking at the line number that is returned. You can also search in a file instead of a directory by using `grep -n keyword fileName.txt`.
## Command 4: 
