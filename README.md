The Expense Management App helps users manage and track their daily expenses by adding, categorizing, and viewing their expenditure trends. This project covers CRUD operations, data storage (both local and cloud), and data visualization.
Technology Stack: React Native, Firebase, or SQLite for storage
 
 Clone the project

```bash
  git clone https://github.com/Kapil-ydv/MoneyControlapp.git
```

Go to the project directory

```bash
  cd expense-tracker-app
```

Optional

```bash
Create a local.properties file with sdk location in the android folder if needed.
```

Install dependencies

```bash
  npm install
```

Start Metro

```bash
  npx react-native start
```

Start the application

```bash
  npx react-native run-android
```

## Generate APK

Go to the root of the project in the terminal and run the below command
https://drive.google.com/file/d/1s6jrcAdt4jHybYxHQ5NmgZwf1R6blzh5/view?usp=drive_link       APK
```bash
  npx react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res
```

Go to the android directory

```bash
  cd android
```

In the android folder, run the following command

```bash
  ./gradlew assembleDebug
```

The APK file will be present in the following path

```bash
  yourProject/android/app/build/outputs/apk/debug/app-debug.apk
```
