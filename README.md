# Saving Reminders

This UIKit project Integrates with the built-in Reminders app made by Apple. It utilizes the built-in app for its data storage by loading and saving reminders directly to and from the built-in app. It adds features not found on the built-in Reminders app. It also leverages the built-in app's Notification features, among other cool tricks.

![](/assets/images/summary.png)

## Technologies
- Swift and UIKit without a Storyboard
- UICollectionViewController, UICollectionViewDiffableDataSource & NSDiffableDataSourceSnapshot
- Custom Store based on EventKit's EventStore to make the app connect to the built-in Reminders app; the OS then helps with collecting the required permissions from the User, for the app to access the Reminders app's database, etc
- Observes changes on the built-in Reminders app, and automatically updates the contents on this project
- Has Objective-C functions and #selectors for assigning delegates
- Programmatic building and constraining of UIView elements
- Filters and splits the data into different categories
- Animates the completion indicator
- Swipe to Delete
- etc.

## Screencast

| **Creating a new Reminder** | |
| :--- | --- |
| <img src="/assets/images/create_reminder.gif" width="300px"> | The Reminder created here will also be available automatically on the built-in Reminders app, shown below. |

| **Exploring the App** | |
| :--- | --- |
| The tabs separate the tasks into Today, Future and All categories, for you to see better the Reminders due for today, and so on. | <img src="/assets/images/explore_app.gif" width="300px"> |

| **Integrations** | |
| :--- | --- |
| <img src="/assets/images/reminders_app_integrations.gif" width="300px"> | The Reminders created using the built-in Reminders app, also appear on this app, as long as the Date and Time is set, as this app specifically wants to categorize those and does not know what to do with the other reminders. |

| **Leveraging Notifications** | |
| :--- | --- |
| When you create a Reminder on this app, the built-in Reminders app reacts by issuing a Notification to the End-User, specially evident if the due date and time is set to now. | <img src="/assets/images/leverage_notifications.gif" width="300px"> |

<sub>All Rights Reserved ©️ 2023</sub>