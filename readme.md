# The suite of apps that invoke daily victory.

- `CVV` -Conqueror's Valor Vault- is a collection of apps that are designed to help people improve their lives in various ways.
- The apps are designed to be used in conjunction with each other, but they can also be used on their own.
- The apps are focussed primarily on users who are affected by mental health issues, specifically executive dysfunction, but they can be used by anyone who wants to improve their lives.
- The apps are designed to be as simple as possible, so that they can be used by anyone, regardless of their technical proficiency.
- The apps and the suite are designed in such a way that the user is always in control of their data and how it is used. This makes it possible for the users to easily share their data with healthcare professionals, if they so choose.

## umbrella app:

- `CVV` is the umbrella app that all the other apps seamlessly integrate with.
- `CVV` is optional, users can decide to use the apps without `CVV` if they want to.
- `CVV` is a platform which allows for easy integration of new apps.

## apps:

- `SSQ` -SoliSquire- is the app that allows users to manage their daily tasks by personal importance over priority.
- `CSM` -ChoreSmith- is the app that allows users to manage their 4-weekly.
- `ELE` -EndeavorLedger- is the app that allows users ledger their activities and how these affect them.

## shared:

- users data is stored in a remote database.
- all apps have access to the same database.
- all users are synced to this database.
- users can only access their own data.
- users are able to make separate accounts for each app.
- ideally users should be able to use all apps with a single account, but they should also be able to use multiple accounts with a single app and are able to merge/ split accounts as they see fit.

## Apps architecture:

    - CVV
         - SSQ
         - CSM
         - ELE
         - any future apps

all these apps are separate apps that are able to run on their own, but they are also able to run in conjunction with each other when connected to the `CVV` app.

### App abbreviations:

- `CVV`: Conqueror's Valor Vault.
- `SSQ`: SoliSquire.
- `CSM`: ChoreSmith.
- `ELE`: Endeavor Ledger.

## end of cvv/readme.md

---

# ChoreSmith.

- In the ChoreSmith’s forge, even solid steel becomes malleable.

## Project description:

- ChoreSmith is an app that allows a user to manage their 4-weekly chores.
- It is part of the Conqueror's Valor Vault, which is a collection of apps that are designed to help people improve their lives in various ways.
- ChoreSmith will help you divide your tasks over a 4-week period by taking your time, effort and energy levels into account.

## Project goals:

- Simple and easy to use.
- Non-intrustive.
- Easy to understand.
- non-confrontational.
- non-judgemental.
- Accessible.
- Easy to use in conjunction with other apps.

## Project features:

- Registering chores with their estimated time spent and effort required.
- Calendar view of chores.
- passing chore done to `EndeavorLedger` when chore is done.
- Adjusting chores to new parameters.

## end of csm/readme.md

---

# EndeavorLedger.

- What's done isn't gone

## Project description:

- EndeavorLedger is an app that allows a user to simply register any activity that they've done and what impact they have had on their energy and mood, so they can have a better understanding of what they can do to improve their mood and energy levels.
- EdeavorLedger is an app that's part of the Conqueror's Valor Vault, which is a collection of apps that are designed to help people improve their lives in various ways.
- The app is designed for it's simplicity, non-intrustiveness and ease of use.

## Project goals:

- Simple and easy to use.
- Non-intrustive.
- Easy to understand.
- non-confrontational.
- non-judgemental.
- Accessible.
- Easy to share data with healthcare professionals.
- Easy to use in conjunction with other apps.

## Project features:

- Register activities, time spent, energy levels and mood.
- View activities, time spent, energy levels and mood.
- high level graphical overview of activities, time spent, energy levels and mood.
- Export data to various formats.
- insights when certain patterns are detected.
- share data with healthcare professionals.

## end of ele/readme.md

---

# SoliSquire.

- "At your service, for this day and this day alone."

## Project description:

- SoliSquire is an app that allows a user to simplify their tasks by looking at the task from the user's feeling perspective instead of their urgency perspective. This will allow the user to have a better overview of which tasks will give them more sense of success and makes the user getting used to this way of prioritizing their tasks.

## Project goals:

- Simple and easy to use.
- Non-intrustive.
- Easy to understand.
- non-confrontational.
- non-judgemental.
- Accessible.
- Easy to share data with healthcare professionals.
- Easy to use in conjunction with other apps.

## Project features:

- Setting tasks. Tasks are only text and can be dragged into one of the 3 priority sections.
- The app will never tell when the user should do a task, but will give them a high level overview of their own priorities.
- The app will not have any notifications by default, but as the app grows with the user, the user can set notifications for certain tasks.
- The app will never state a task is not done or forgotten.
- Whenever a user finishes a task, the user can drag the task into the done section.
- The user can select whether a task is a recurring task, so when the task is dragged to the done section, it's not archived, but moved back to the suggestions section.
- The app will reset daily, so the user can start fresh every day.
- The user will be able to select a set of tasks that are recurring and will be added to the suggestions section every day.
- If theres a task that's been postponed for n days, the app will minimize that task, so the user can focus on the tasks that are more important to them.
- This app will be part of the Conqueror's Valor Vault, which is a collection of apps that are designed to help people improve their lives in various ways.
- This app is NOT designed as a task manager, but rather as a task prioritizer.

end of ssq/readme.md

---

## end of document
