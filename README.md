# who-is-there

https://brew.sh
brew install node    //версии node v18.16.0 (npm 9.5.1)
brew install watchman
brew tap homebrew/cask-versions

//  для мак переменные окружения,  для win https://reactnative.dev/docs/environment-setup
export ANDROID_HOME=$HOME/.zshrc/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/platform-tools

//диагростика подключений
npx @react-native-community/cli doctor


IOS
XCode 14
npm install
expo start


Android
Android Studio 2022.2.1
запустить андроид студию
только потом expo start --android
// проверить не вышло

Web
npm install
expo start --web