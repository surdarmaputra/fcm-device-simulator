# fcm-device-simulator
Simple web app to test Firebase Cloud Messaging functionality.
Adopted from [https://github.com/firebase/quickstart-js/tree/master/messaging](https://github.com/firebase/quickstart-js/tree/master/messaging) with some modifications. It can be useful to test Firebase Cloud Messaging functionality from your backend application.

See [this documentation](https://github.com/firebase/quickstart-js/tree/master/messaging#firebase-cloud-messaging-quickstart) for the quickstart guide.

## Getting Started
1. Create a project on [Firebase Console](https://console.firebase.google.com).
2. Install [Firebase CLI](https://firebase.google.com/docs/cli/) by running `npm install -g firebase-tools`. (Make sure you have Node.js and npm already installed).
3. Configure Firebase CLI credential using `firebase login` and follow the steps shown in the console.
4. Go to project directory and change the value of `default` property inside `.firebaserc` file with the name of project you have created.
5. Run `firebase server` to fire up a local server containing your project
6. or run `firebase deploy` to upload your project into [Firebase Hosting](https://firebase.google.com/docs/hosting/).
7. After deploying into Firebase Hosting, you can access your project from URL `<your-project-name>.firebaseapp.com`.

## Credits

- [https://github.com/firebase/quickstart-js/tree/master/messaging](https://github.com/firebase/quickstart-js/tree/master/messaging)
- [Material Design Lite](https://getmdl.io/)
