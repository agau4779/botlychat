# Set up Firebase and tools

Download npm:
https://www.npmjs.com/get-npm

Set up Firebase project
https://codelabs.developers.google.com/codelabs/firebase-web/#2

Download Firebase CLI:
```
npm -g install firebase-tools
```

If it does not work, run `npm cache clean --force`

Deploy this project:
```
git clone https://github.com/agau4779/botlychat

firebase login
firebase use --add [your-project-id]

cd functions
npm install
cd ..

firebase deploy 
```

# Firebase SDK for Cloud Functions Codelab - Final code

This folder contains the final code of the [Firebase SDK for Cloud Functions
](https://codelabs.developers.google.com/codelabs/firebase-cloud-functions/).

You can use this app directly if you'd like to see the finished app but before you do follow the "Create a Firebase Project and Setup" step of the [Codelab instructions](https://codelabs.developers.google.com/codelabs/firebase-cloud-functions/)

If you'd like to follow the step by step codelab start with the [cloud-functions-start](../cloud-functions-start) directory.
