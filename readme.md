# The suite of apps that invoke daily victory.

## umbrella app:

- `CVV` is the umbrella app that all the other apps seamlessly integrate with.
- `CVV` is optional, users can decide to use the apps without `CVV` if they want to.
- `CVV` is a platform which allows for easy integration of new apps.

## apps:

- `SSQ` is the app that allows users to manage their daily tasks by personal importance over priority.
- `CSM` is the app that allows users to manage their 4-weekly.
- `ELE` is the app that allows users ledger their activities and how these affect them.

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
