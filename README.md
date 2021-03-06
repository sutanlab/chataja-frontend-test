# ChatAja Frontend Test

## Table of contents
- [ChatAja Frontend Test](#chataja-frontend-test)
  - [Table of contents](#table-of-contents)
  - [Stack Used](#stack-used)
  - [Build Setup](#build-setup)
  - [Result](#result)
    - [Build APK](#build-apk)
    - [Screenshots](#screenshots)

## Stack Used
- React Native
- Firebase

## Build Setup
1. Clone repository
`$ git clone https://github.com/sutanlab/chataja-frontend-test.git`

1. Install depedencies
```bash
$ yarn install
```

3. Setup your environment variable in `.env` files (if not exists, create your own).
```env
FIREBASE_API_KEY = xxxx
FIREBASE_AUTH_DOMAIN = xxxx
FIREBASE_DATABASE_URL = xxxx
FIREBASE_PROJECT_ID = xxxx
FIREBASE_APP_ID = xxxx
```

4. Available scripts
```bash
# start development server
$ yarn android
$ yarn ios

# build app android
$ cd android/ && ./gradlew assembleRelease
```

## Result

### Build APK
> Link url: https://drive.google.com/file/d/1EECQuCbpmYEXT5vZxxp7lQPOjBVdQpSe/view?usp=sharing

### Screenshots

<p float="left">
  <img src="https://raw.githubusercontent.com/sutanlab/chataja-frontend-test/master/screenshots/splash.jpeg" width="200" height="350" alt="Splash">
  <img src="https://raw.githubusercontent.com/sutanlab/chataja-frontend-test/master/screenshots/login.jpeg" width="200" height="350" alt="Login" >
  <img src="https://raw.githubusercontent.com/sutanlab/chataja-frontend-test/master/screenshots/register.jpeg" width="200" height="350" alt="Register">
  <img src="https://raw.githubusercontent.com/sutanlab/chataja-frontend-test/master/screenshots/home.jpeg" width="200" height="350" alt="Home">
  <img src="https://raw.githubusercontent.com/sutanlab/chataja-frontend-test/master/screenshots/chatroom.jpeg" width="200" height="350" alt="Chat Room">
  <img src="https://raw.githubusercontent.com/sutanlab/chataja-frontend-test/master/screenshots/account.jpeg" width="200" height="350" alt="Account">
</p>

---

Regards, Sutan Gading Fadhillah Nasution.