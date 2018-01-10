# Android-Projects
A List of Android App I Created


# [Viusal Rolodex App]( https://github.com/Raywilliams01/MobileTakeHomeInterView.git)
    This goal is create a visual rolodex app.  App will get some sample data in JSON form, display the data in a cards that you can navigate with your fingers. Showcases individual cards against a colored background, and allows you to move between them horizontally.  
    
1. Create a Viusal Rolodex App
2. Pull data from JSON
3. User must be able to
    * Scroll Horizontal
    * View individual card objects with the following fields:
        *   lastName
        *   firstName
        *   email
        *   company
        *   startDate - date and time in ISO 8601 format
        *   bio - A small paragraph that may contain basic Markdown (asterisks to represent bold, underlines to represent italics)
        *   avatar - a URL for a 300x300px image

![screenshot_20180110-073903](https://user-images.githubusercontent.com/10648696/34773788-ee5a7faa-f5da-11e7-948e-ad0e0f6e4323.png)
![screenshot_20180110-073909](https://user-images.githubusercontent.com/10648696/34773792-f1ebb292-f5da-11e7-8d39-005b2d812e86.png)

 
    
If you are fimilar with github open your terminal and paste in the following code

    git clone https://github.com/Raywilliams01/MobileTakeHomeInterView.git


#  [Inventory App](https://github.com/Raywilliams01/InventoryApp.git)

The purpose of this project is design and create the structure of an Inventory App which would allow a store to keep track of its inventory of products. The app will need to store information about price, quantity available, supplier, and a picture of the product. It will also need to allow the user to track sales and shipments and make it easy for the user to order more from the listed supplier.

### Project Includes
    Storing information in a SQLite database
    Integrating Android’s file storage systems into that database
    Presenting information from files and SQLite databases to users
    Updating information based on user input.
    Creating intents to other apps using stored information.


![screenshot_20180110-073930](https://user-images.githubusercontent.com/10648696/34773841-21e6a592-f5db-11e7-84e1-97682ad6f357.png)



### Download 
    If you are fimilar with github open your terminal and paste in the following code

    git clone https://github.com/Raywilliams01/InventoryApp.git



# [Habit Tracking App](https://github.com/Raywilliams01/HabitTrackerApp.git)

    The goal of this project is design and create the structure of a Habit Tracking app which would allow a user to store and track their habits over time. This project will not have any UI components; instead, it will focus on what happens behind the scenes, practicing how to design and implement a simple database.


````java
 private static final String SQL_CREATE_ENTERIES =
            "CREATE TABLE " + HabitContract.HabitEntry.TABLE_NAME +
                    " (" +
                    HabitContract.HabitEntry._ID + " INTEGER PRIMARY KEY," +
                    HabitContract.HabitEntry.COL_WALK_THE_DOG + " " + COL_TYPE_TEXT + ","
                    + HabitContract.HabitEntry.COL_FEED_THE_DOG + " " + COL_TYPE_TEXT +","
                    + HabitContract.HabitEntry.COL_NUMBER_OF_DOG_WALK + " " + COL_TYPE_INTEGER + ")";

    private static final String SQL_DELETE_ENTRIES =
            "DROP TABLE IF EXISTS " + HabitContract.HabitEntry.TABLE_NAME;

````

### Download 
    If you are fimilar with github open your terminal and paste in the following code

    git clone https://github.com/Raywilliams01/HabitTrackerApp.git



# [Search Book App](https://github.com/Raywilliams01/Book)

    The goal of this project is design and create the structure of a Book Listing app which would allow a user to get a list of published books on a given topic. You will be using the google books api in order to fetch results and display them to the user.

* Fetching data from an API
* Using an AsyncTask
* Parsing a JSON response
* Creating a list based on that data and displaying it to the user.



![quizapp](https://user-images.githubusercontent.com/10648696/31171887-671d87f6-a8cf-11e7-8dd4-e1edaaf9488f.png)

### Download 
    If you are fimilar with github open your terminal and paste in the following code

    git clone https://github.com/Raywilliams01/Book
