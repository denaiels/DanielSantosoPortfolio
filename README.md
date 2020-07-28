# Daniel Santoso's Portfolio
Hi my name is Daniel Santoso!

## [Project 1: Indonesian Profanity Checker](https://github.com/denaiels/Project_Indonesian-Profanity-Checker)

*Click the title above, to open the Github Repository of this project*

**Made by Team:**
1. Albert Lilian Thamson (2201754412)
2. **Daniel Santoso (2201756506) (me)**
3. Luwis Lim (2201761771)
4. Steven Odolf Yuwono (2201758045)

**Description:**

Indonesian Profanity Checker is my final project for the Natural Language Processing course in my Semester 4 of Computer Science Major at BINUS University.

Indonesian Profanity Checker is a program to check whether an input sentence contains profane/harsh words or not. In this project, the dataset used is a list of YouTube video comments from the Indonesian YouTuber Ericko Lim, which mostly is of Indonesian language (many are slang languages) and these comments tend to have profane/harsh words within them, and each of the comment is tagged as 'PROFANE' or 'CLEAN'. Our Indonesian Profanity Checker works using Bag-of-Words method, where in the training process, it is fed with the dataset we have provided and it learns which words are profane by counting the words' occurence in sentences that are considered profane or not profane. We also used Indonesian common stopwords to filter the dataset.

**My contributions:**
- Discussed with the team about the idea and brainstormed together until we get the final decision to make this project
- Do the research to accomplish the goals that we have set
- Took part in cleaning the dataset used
- Coded most of the program in Python programming language

**Results:**

We tried the program with 3 versions of dataset splits, where the ratio is train:test, those are 70:30, 80:20, and 90:10. From the experiment we did, we found out that the most optimal dataset to use is the 70:30 ratio, because it gets the highest accuracy among the others.

*DISCLAIMER: Examples shown may contain words that are offensive.*

70:30 Data Split
![](/profanity/percobaan(70).png)
![](/profanity/acc(70).png)

80:20 Data Split
![](/profanity/percobaan(80).png)
![](/profanity/acc(80).png)

90:10 Data Split
![](/profanity/percobaan(90).png)
![](/profanity/acc(90).png)

## [Project 2: Transetter](https://github.com/denaiels/Project_Transetter)

*Click the title above, to open the Github Repository of this project*

**Made by Team:**
1. Albert Lilian Thamson (2201754412)
2. **Daniel Santoso (2201756506) (me)**
3. Kevin Gunawan (2201829981)
4. Luwis Lim (2201761771)
5. Rio Nagano (2201767232)
6. Steven Odolf Yuwono (2201758045)

**Description:**

Transetter is my final project for the Software Engineering course in my Semester 4 of Computer Science Major at BINUS University.

Transetter is an application that focuses on transportation. Transetter is an application that has a unique feature that other transportation apps don’t have, that is, Transetter can order multiple means of transportation to get the user to the destination that they want. Usually, a transportation app, mainly the ride ordering apps, only provide one mean of transportation from location to the destination, such as Gojek where to get from point A to point B users can only choose 1 mean of transportation, either it is Go-Ride or Go-Car. Transetter gives its users the opportunity to choose multiple means of transportation to get from point A to point B, C, D, etc. For example, if you want to go from point A to point Z, then after setting the location and destination on the app, the app will provide choices for the users to choose. The choices are the routes that will be taken by the user. On every route choice, there can be multiple means of transportation and multiple stops before reaching the final destination, and there will also be the details on distance, estimated time of arrival (ETA), and price. An example of the simple choices from point A to destination point Z is as follows:

Choice 1 : Distance 3.8 km, ETA: 13 minutes, Total price Rp25.000,-

•	Point A to Point Z (using Gojek, Rp25.000,-)

Choice 2 : Distance 4.5 km, ETA: 30 minutes, Total price Rp13.500,-

•	Point A to Bus Stop B (using Transjakarta, Rp3.500)

•	Bus Stop B to Point Z (using Gojek, Rp10.000,-)

Users can choose between using 1 mean of transportation and faster but more expensive, or using 2 means of transportation that is cheaper, but longer on the way. This is the unique feature that Transetter provides for its users. This app not only provides those choices to guide the users, but users can also book the orders through the app itself, except for a few vendors that have their own app, then Transetter will automatically redirect the user to the app related. This makes Transetter unique and very much helpful for users.

**My Contributions:**
- Initiated the idea of a transportation mobile app that have such unique features
- Gave the name of the app, Transetter
- Define the core aspects of the application, such as the purpose and features
- Designed the logo of Transetter.

**UI Design:**

Here is the UI Design of Transetter made by my colleague, Steven Odolf Yuwono:

| Splash Screen | Main Menu | Saved Place |
| ----------- | ----------- | ----------- |
| ![](/transetter/splash_screen.jpg) | ![](/transetter/main_menu.jpg) | ![](/transetter/saved_place.jpg) |
| Select Destination | Select Transportation | Navigation |
| ![](/transetter/destination_screen.jpg) | ![](/transetter/select_transportation.jpg) | ![](/transetter/navigation.jpg) |
