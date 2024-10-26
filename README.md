# CS360: Mobile Architect & Programming

Weight Tracker 360 Application

Requirements and Goals of Weight-Tracking application: My  application was designed to track the daily weight of the user. The goals (features) for this application included a database to store user profiles, weight entries and the goal weight. The UI needs a login screen, main screen (dashboard) to input key data and display data (grid and chart) and ways to modify weight entries (CRUD operations on the database). 

Needs addressed by Weight-Tracking application: My application was designed to help user live a healthier life by giving them the tools to track their weight and set goals. The visual components of my application (chart) gives the user a clear trend of their weight and whether they are on the right path or not. Notifications are also incorporated to congratulate the user's accomplishment when they reach their goal.

Necessary screens and features needed to support the user needs: The clean and simple login screen was needed for account creation and for existing users to login. The dashboard screen was needed for the centralized hub for the weight tracking functionality, this screen rpovided ways to input your weight, scroll through recent weight entries (and modify if needed) and see (chart) your progress over time (as well as the goal line for your goal weight). The dashboard has a toolbar icon to navigate you to the settings screen which include the weight goal input and a toggle for SMS notifications. 

Design Success: I beleive my design was successful in that the UI was simple yet engaging through its consistent layout, toolbar placement, and interactive graph for trend visualization. The error handling has clear messages and input validation to ensure a user friendly experience. The simplicity and feedback (Toast messages) give the user clear indicators that everything works as intended (or give you a clear error message). The minimal learning curve will prevent users from getting agitated.

Process of coding: I approached the coding of my application through a iterative approach. Breaking down the features into smaller stories / items (functions), helped me make a complex project into a manageable one. The constant developing and testing in smaller increments helped me identify errors quicker and prevent future roadblocks. I plan to continue this approach as it not only makes development more manageable but also improves code quality and reduces debugging time by catching issues early in the development cycle.

Testing Code Quality: I practiced unit testing and integration testing. The unit testing was critical to verify everything was working as intented and this approach helped me to ensure the valid and invalid inputs performed as intended for the weight entries. The integration testing was crucial when I implemented the database as I had to ensure the weight and goal entries were saved properly to the database as well as the usernames and passwords. The debugging tools on Android Studio and Emulator helped me catch a lot of these errors while providing a way for me to verify my UI was functioning as intended. I had to implement some logs on more complex tasks which helped me identify bugs that were only caught in runtime.

Innovation to overcome challenges: The backend (database and CRUD operations) were challenging but I wanted the user to visualize (Chart Graph) their weight-loss journey (and not just a GRID component with recent weight entries) and I elected to use the library MPAndroidChart by Philipp Jahoda. This library provided a way to visual the data the user inputed into their weight journal. Learning my way around this library was challenging but the resulting graphical representation of weight trends provided substantial value to user making the effort rewarding.
   
Specific component in which my skills are most demonstrated: I beleive the robust and functional database (CRUD operations) shows my skill set in handling data and the implementation of a Chart/Graph library shows my technical ability to research and integrate third-party libraries to enhance the user experience. The problem-solving with the real time database updates and syncing changes with the chart was challenging but represents my growth as a developer.  
 



