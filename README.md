# CS360-Mobile-Architect-Programming-
# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The Event-Tracking App helps users manage and track their upcoming events easily. Users can create accounts and log in to the app. They can see all scheduled events in a grid display and have options to add, edit, or delete events. The app keeps event details and user information secure in a database and sends reminders on the day of each event. This way, users will never miss important dates. The app is designed for convenience and reliability, making it a useful tool to keep schedules organized.

# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
Key features of the app include:

•	Login/Signup Screen: This screen lets users log into their accounts or create a new account if they use the app for the first time. The design should be simple and make both options easy to find.

•	Event Details Table: This table will store important details about each event, such as the name, date, time, and description.

•	Event Grid Screen: This screen shows all upcoming events in a grid format, allowing users to see their schedules quickly.

•	Add/Delete Event Mechanism: Users should be able to add new events by entering relevant details (time, description, etc.) and remove events they no longer wish to track.

•	Event Reminder System: A mechanism to send notifications to users on the day of the scheduled event, ensuring they are reminded on time.

This application will help people manage their time better. It will be easy to use and well organized, focusing on user login, event management, clear displays of events, and timely notifications. The user-friendly design will guide users through the app, helping them manage events effectively. This will greatly improve the user experience by addressing the most important aspects of the application.

# How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
To build the Event-Tracking App, I followed a clear plan. I divided the project into smaller tasks, like creating the login feature and managing events. I worked on these tasks one at a time. I tested each feature thoroughly before starting the next one. I constantly improved the design and functionality based on testing results, always keeping the user experience in mind to create an easy-to-use and error-free interface. These strategies, like working step by step and using modular coding, can help make future projects more efficient and of higher quality.
# How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
I tested my code to make sure it worked. I used manual testing and debugging. I ran the app on different devices and emulators and checked each feature step by step to see if it functioned correctly. For example, I tested the login by entering valid and invalid credentials to check how it handled errors. When I found issues, I used logs and debugging tools to figure out what went wrong and fix them.
This process is important because it helps ensure the app is reliable and gives users a good experience. Testing uncovered small bugs and edge cases I didn’t think of, like how the app behaved when there were no events. It allowed me to catch errors early and feel confident that my app would work well in real-life situations.
# Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
During testing, the app would crash every time I logged in, which presented a significant challenge. After debugging, I discovered the issue was in the XML layout file, where a button was mistakenly named as a `TextView`. This caused a mismatch in the code, as the app tried to interact with the element as a button but couldn’t locate the correct resource type.  
To resolve this, I carefully reviewed the XML layout file and corrected the naming error. I also added proper IDs and ensured all elements matched their references in the code. Additionally, I tested the app again to confirm the fix and prevent similar issues.  
This challenge emphasized the importance of attention to detail when designing layouts and maintaining consistency between XML and Java/Kotlin code. Moving forward, I’ll be more vigilant with naming conventions and use tools like IDE warnings and layout previews to catch such errors early.
# In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
I demonstrated my skills in setting up the login and account creation features of the app. I used an SQLite database to securely store and retrieve user information, ensuring both functionality and security.
The login system checks input to prevent mistakes, while the account creation feature allows new users to easily add their information to the database. I also added error messages to inform users when their login details are incorrect or if a username is already in use.
This work shows my ability to create secure and user-friendly authentication systems, providing a smooth experience for users accessing the app.
