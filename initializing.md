# React Natice [Link]( https://reactnative.dev/)

## 1. Install Software
###  1. Nodjs [Link](https://nodejs.org/en/) 
###  2. JDK [Link](https://learn.microsoft.com/en-us/java/openjdk/download#openjdk-17)
###  3. Android Studio [Link](https://developer.android.com/studio) 

## 2. Open Android Studio
### 1. Click On More Action
### 2. Click On SDK Manager
### 3. Click On SDK Platform 
```
Check the following: Which You a Android Version
 ```
## 4. Clink on SDK Tools
### Check the following:
#### 1. Androd SDK Command-line Tools (latest)
#### 2. Google play Licensing Libaryath of Androd SDK Location:
```
C:\Users\atul2\AppData\Local\Android\Sdk
```
## 6. Configure the ANDROID_HOME environment variable
### 1. Search  environment variables
### 2. Click On environment variables
### 3. Click on New to create a new ANDROID_HOME user variable that points to the path to your Android SDK:


## 7. if Check ANDROID_HOME environment variable
### 1. Open powershell
### 2. Copy and paste Get-ChildItem -Path Env:\ into powershell
### 3. Verify ANDROID_HOME has been added

## 8. Add platform-tools to Path
### 1. Search  environment variables
### 2. Click On environment variables
### 3. Select the Path variable.
### 4. Click Edit.
### 5. Click New and add the path to platform-tools to the list.
```
C:\Users\atul2\AppData\Local\Android\Sdk\platform-tools
```

## 9. Run this command as cmd
### 1. Ununstall Pakages
```
npm uninstall -g react-native-cli @react-native-community/cli
```
### 2. Create a Project 
```
npx react-native@latest init AppName
```
### 3. Add file in Android Folder 
file name - local.properties
```
sdk.dir=C\:\\Users\\atul2\\AppData\\Local\\Android\\Sdk
```

### 4. Start a Project
```
npm start
```
