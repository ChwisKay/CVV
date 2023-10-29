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
