# Personal_Expense_Tracker
This project is make for expense tracker for personal that use Flutter for FrontEnd and Node.Js for BackEnd and SQLite for Database.

I. BackEnd

_Create Project Folder and Install Dependencies
```
mkdir expense-tracker-backend
cd expense-tracker-backend
npm init -y

npm install express jsonwebtoken bcrypt sqlite3 body-parser
```

II. FrontEnd

1.Create Flutter Project
```
flutter create expense_tracker
cd expense_tracker
```
2.Install Dependencies (open pubspec.yaml)
```
dependencies:
  flutter:
    sdk: flutter
  dio: ^5.0.0
  flutter_secure_storage: ^5.0.2
```
then run 
```
flutter pub get
```
