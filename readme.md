# TownChooser

##Television news producer scripting aid.

In October of 1997, I accepted a producer position at KAIT-TV in Jonesboro, Arkansas. I was producing the six o'clock news. What might have been somewhat amazing to many was that KAIT was rather advanced for a small station in a single station market. They were completely computerized in the newsroom. Each reporter and producer station had a computer running Windows&#153; 95 and Tektronix NewStar&copy; software. It didn't take me long at all to get comfortable with the software.

There was a problem, however. During the tease before each commercial break, the anchors were to read short one line comments about upcoming stories. During this tease the producer was to write an introductory element that mentioned the names of three of the towns and communities that were in the station's market or coverage area. Each producer had a list of the three hundred fifty or so communities and was supposed to randomly choose three of them for each tease. There were at least three to five teases per newscast.

As a producer, I felt I had enough work to do and I didn't need to keep track of which communities I had used and which I hadn't. Management and the consultants wanted these communities mentioned before every break.

The result was the birth in late 1997 of _Town Chooser Version 1.0._ This simple program used a text file to keep a list of the towns in and randomly selected three towns. After the towns were selected, they were placed in the computer's clipboard and the producer could then paste them into their script in NewStar&copy;. The anchor was then able to read "When we return for our friends in Cardwell, Swifton, and Canebreak . . . "

The problem with _Town Chooser 1.0_ was that there was no way for the average user to edit the communities. I had written the application pretty hastily and when I created the text file containing the towns from the list of towns the producers had to work with I ended up having misspellings of some towns and typos in the others. Whenever we discovered a town that had a typo or was misspelled I had to go into the text file with Notepad and correct the town. The problem with that was, as with most users, the other producers had difficulty remembering to write down the town that was misspelled and let me know about it. Also, while it was easy to use, it still required some explanation and training for new producers.

It's been many years since I left KAIT.  The news director contacted me saying some of the producers still liked to use the program. They needed, however, to be able to edit the towns. I also realized that other stations might be able to use this same type of application if it had editing capabilities.

_Town Chooser 2.0_ was the result. This version used an actual database engine and allowed for the adding, editing, and deleting of town names. It also includes an HTMLHelp file (that this site is based on), a PowerPoint training demonstration, and a licensing agreement. Future versions of the program were planned to provide the ability to pronounce community names on those computers having sound equipment.