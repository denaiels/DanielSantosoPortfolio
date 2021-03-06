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
![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/profanity/percobaan(70).png)
![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/profanity/acc(70).png)

80:20 Data Split
![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/profanity/percobaan(80).png)
![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/profanity/acc(80).png)

90:10 Data Split
![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/profanity/percobaan(90).png)
![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/profanity/acc(90).png)

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
| ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/transetter/splash_screen.jpg) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/transetter/main_menu.jpg) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/transetter/saved_place.jpg) |
| Select Destination | Select Transportation | Navigation |
| ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/transetter/destination_screen.jpg) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/transetter/select_transportation.jpg) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/transetter/navigation.jpg) |

## [Project 3: The Relationship Between People's Music Preferences and Their Health Lifestyle](https://github.com/denaiels/Project_Relationship-Music-Health)

*Click the title above, to open the Github Repository of this project*

**Made by Team:**
1. Albert Lilian Thamson (2201754412)
2. **Daniel Santoso (2201756506) (me)**
3. Luwis Lim (2201761771)
4. Steven Odolf Yuwono (2201758045)

**Description:**

This project is my final project for the Machine Learning course in my Semester 4 of Computer Science Major at BINUS University.

The project is to make a research to determine whether one's music preferences are affects one's health lifestyle, specifically one's smoking habits. This project uses 2 datasets, each with the same columns of many music genres (how much does a person like a music genre from 1-5) and their smoking habits (smoker or not), but the difference is that 1 dataset is filled by all Slovakian nationalities and the other dataset is filled by all Indonesian nationalities. The Slovakian dataset also have more rows than of the Indonesian dataset.

The methods we use to process the data and get insight are:
1. Linear Regression
2. Polynomial Regression
3. Support Vector Machine (SVM)
4. Decision Tree
5. K-th Nearest Neigbour (KNN)
6. Random Forest

To see the full explanation on this research, please kindly open our report on the folder "Report" with the file name of "Laporan Project Machine Learning_AlbertDanielLuwisSteven"

**My Contributions:**
- Discussed and brainstormed together with teammates to get the idea of the project.
- I initiated the idea of the project
- Took part in cleaning the dataset
- Coded the KNN and Random Forest models of the project
- Made the analysis for KNN and Random Forest results
- Compiled all the analysis of all the models from my teammates
- Made the conclusion of the project

**Results:**

Form the various methods that we used, the best result that we obtain was using the Random Forest method. Using the Random Forest model, the Slovakian dataset got an accuracy of 66.59%, meanwhile the Indonesian dataset got an accuracy of 93%. For the conclusion, we found out that people's music preferences does not relate or affect their smoking habits. The Slovakian dataset shows very low relations between music preference and smoking habits, but the Indonesian dataset shows a little bit of relation between some music genre preferences and the smoking habit of the person who likes that specific music genre, that is Rock n Roll and Punk.

Here are the results...

Slovakian Dataset using Random Forest:

![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/lifestyle/dataslovak.png)

Indonesian Dataset using Random Forest:

![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/lifestyle/dataindo.png)

## [Project 4: Xtream Chaser](https://github.com/denaiels/Project_XtreamChaser)

*Click the title above, to open the Github Repository of this project*

**Made by Team:**
1. Albert Lilian Thamson (2201754412)
2. **Daniel Santoso (2201756506) (me)**
3. Kevin (2201751530)
4. Rio Nagano (2201767232)

**Description:**

Xtream Chaser is my final project for the Human-Computer Interaction course in my Semester 4 of Computer Science Major at BINUS University. The project is to make a website design using HTML, CSS, and jQuery to showcase a new upcoming game called Xtream Chaser. My website has 5 pages, Homepage, Gallery, Characters, Lore, and Pre-Register Beta. The website is not yet connected to any database so it cannot receive any input of data, so this is just the design and prototype.

**My Contributions:**
- Designed the blueprint of the website
- Coded the header and footer of the website
- Coded most of the HTML and CSS on all pages (Homepage, Gallery, Characters, Lore, and Pre-Register Beta)
- Coded using jQuery to make the image slider on the homepage

**Screenshots:**

In case you don't want to open the HTML by yourself, I have provided screenshots of all the pages of my website. Here it is...

| Part | Screenshot |
| ----------- | ----------- |
| Homepage | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/xtream/homepage.png) |
| Gallery | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/xtream/gallery.jpg) |
| Characters | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/xtream/characters.png) |
| Lore | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/xtream/lore.png) |
| Pre-Register Beta | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/xtream/preregister.png) |

## [Project 5: PopLegal](https://github.com/denaiels/Project_PopLegal)

*Click the title above, to open the Github Repository of this project*

**Made by:**

Daniel Santoso (2201756506)

**Description:**

PopLegal is my mid exam project for the Software Engineering course in my Semester 4 of Computer Science Major at BINUS University.

PopLegal is an mobile-based application that aims to provide legal consultation between users and legal professionals. Features of PopLegal are:
- Choose a legal professional for consultation between an Advocate or a Notary
- Approval by the chosen legal professional
- Chatting between the two parties
- Giving feedback for both parties

**UI Design:**

| Splash Screen | Prompt | Login |
| ----------- | ----------- | ----------- |
| ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/poplegal/1_splash_screen.png) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/poplegal/2_prompt.png) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/poplegal/3_login.png) |
| Sign Up | Choose Service | Select an Advocate/Notary |
| ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/poplegal/4_sign_up.png) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/poplegal/5_choose_service.png) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/poplegal/6_select_advocatenotary.png) |
| Overview | Overview (scrolled) | Chat |
| ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/poplegal/7_overview.png) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/poplegal/8_overview(scrolled).png) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/poplegal/9_chat.png) |
| Feedback |
| ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/poplegal/10_feedback.png) |

## [Project 6: CoronaMana](https://github.com/denaiels/Project_CoronaMana)

*Click the title above, to open the Github Repository of this project*

**Made by:**

Daniel Santoso (2201756506)

**Description:**

CoronaMana is my mid exam project for the Human-Computer Interaction course in my Semester 4 of Computer Science Major at BINUS University.

CoronaMana is a mobile-based application with a purpose to encourage people to stay away from areas indicated with COVID-19 traces so that infection count can be minimalized.

Features:
- Giving location information of people indicated with COVID-19 infection (ODP, PDP, Suspect, Positive, and Cured)
- Giving information of the history of places where the infected person went
- Live count of COVID-19 infection in Indonesia (cases, death, and cured)
- Giving tips to prevent infection of COVID-19
- Report feature to report COVID-19 cases around the user

**UI Design:**

| Splash Screen | Prompt | Sign Up |
| ----------- | ----------- | ----------- |
| ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/coronamana/1_splash_screen.png) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/coronamana/2_prompt.png) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/coronamana/3_daftar.png) |
| Sign In | Map | Report |
| ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/coronamana/3_masuk.png) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/coronamana/4_peta.png) | ![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/coronamana/5_lapor.png) |

## [Project 7: Wine Classification](https://github.com/denaiels/Project_Wine-Classification)

*Click the title above, to open the Github Repository of this project*

**Made by Team:**
1. **Daniel Santoso (2201756506) (me)**
2. Axel Jeremy (2201756140)

**Description:**

Wine Classification is my final project for the Artificial Neural Network course in my Semester 4 of Computer Science Major at BINUS University. This is a program that can classify the quality of a wine based on a few categories, those are volatile acidity, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol. StandardScaler and PCA with 4 components are used to do feature engineering. The model used for classification is Backpropagation Neural Network (BPNN) and the output is the accuracy of model.

**My Contributions:**
- Discussed the project with teammate
- Coded all the codes needed

**Results:**

The model gets 52% accuracy:

![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/wine/classification.png)

## [Project 8: Customer Behaviour Clustering](https://github.com/denaiels/Project_Wine-Classification)

*Click the title above, to open the Github Repository of this project*

**Made by Team:**
1. **Daniel Santoso (2201756506) (me)**
2. Axel Jeremy - 2201756140

**Description:**

User Behaviour Clustering is my final project for the Artificial Neural Network course in my Semester 4 of Computer Science Major at BINUS University. This is a program that can cluster the customers according to their behaviour. PCA with 3 components are used to do feature engineering. The model used for clustering is Self-Organizing Map and the output is the visualization of the model.

**Results:**

Visualization of the model after 5000 epochs:

![](https://raw.githubusercontent.com/denaiels/DanielSantosoPortfolio/master/customer/clustering.png)
