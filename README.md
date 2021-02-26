# SemesterProject2
Introduction

Mobile App Development is important field nowadays, as smartphones have become very common and an integral part of everyday life. Thus, android apps can be helpful in completing daily life tasks like connecting with friends, checking weather updates, helping with daily exercises, etc. My app is a fitness app named Stay Fit. Basically, this helps in performing information about different exercises and track daily exercise schedule. The motivation behind creating this app is to help others in staying fit. I used somewhat similar apps  for my daily workout schedule available on Google Play Store like Fitify: Workout Routines & Training, 10 Daily Exercises,  Home Workout- No Equipment, etc. 



Requirements

The basic requirements gathered and analyzed for all fitness apps include various different exercises for working out, keeping track of workout days (days in which workout was completed and days missed), keeping track of calories, setting  a rest time between exercises, etc. The requirements gathered from other similar apps and analysis of my daily workout schedule helped me in deciding which basic features are to be integrated in my android app.


Features

The Android App -Stay Fit has 10 different exercises for daily workout. The most important feature is that it is for people that have no equipment for fitness workout and can be easily done at home or any place. It has a built in calendar with markup boxes for tracking workout routine and schedule. There is a settings menu where rest time between different exercises is managed i.e. Workout Difficulty. Workout Difficulty settings of workout include Easy, Medium and Hard which can be changed by the user. These modes decide number of reps  of each exercise. A progress bar between each exercise, countdown rest time clock between exercises,   and workout completed notification is also available in Stay Fit. There is also language support for Urdu language.


The App has following layouts:
1.	activity_finish_exercise.xml
2.	calendar.xml
3.	activity_main.xml
4.	calendar_item.xml
5.	chosen_exercise.xml
6.	difficulty.xml
7.	exercise_start.xml
8.	rest_time.xml
9.	row_list.xml
10.	settings.xml

The layout which appears  when user downloads or starts is “activity_main.xml”. Other layouts appear depending on which option the user selects.
The App has following Java Classes:
1.	SettingsActivity
2.	ExerciseStartActivity
3.	DifficultyActivity
4.	BuildConfig
5.	R
6.	SavingData
7.	Exercise
8.	CalenderView
9.	MainActivity
10.	DBAdapter
11.	FitnessExercise
12.	InputFilterMinMax
13.	CustomAdapterSettings
14.	ChosenExerciseActivity
15.	ChangeRestTimeActivity
16.	AppInformation
17.	FinishExerciseActivity
18.	CalendarAdapter

It also has many related files in drawable resources . Other definition are done in  values folder. It also has a testing java file. MainActivity, SettingsActivity, ExerciseStartActivity, DifficultyActivity, FinishExerciseActivity, ChangeRestTimeActivity, ChosenExerciseActivity and CalendarAdapter
are the building block or basic java classes which interact with other activities for data retrieval or storage. No specific architecture is followed in this app.



Implementation of features

Firstly, in android manifes file “.MainActivity” is loaded using java class. Main Activity. A database is available “DBAdapter” for storing and managing of data. MainActivity loads layout file ’activity_main.xml” and also checks and connects with data folder having Java classes of “SavingData”,”AppInformation”, etc. “CalenderView” manages calender layout and displays required data. “ChangeRestTimeActivity” helps user control rest time between exercises. “Difficulty exercise” helps user change mode of exercises. “R” stores ids of different elements used.
Testing

Unit testing and app testing is also implemented in the project. ExampleInstrumentedTest is the android test class which uses assertsEqual to load and test app package. MainActivity and ExerciseStartActivity also is used for testing by coding and running the app.
Conclusion

Stay Fit is a very useful app for daily workout fitness at home without requirement of any fitness equipment. The design principle are very simple and basic  having database management , list views, drawable resources and animation images to guide a user during exercise. The design of the app is simple and easy to use by the user. Language support for Urdu language helps user who are unable to understand English language.  



