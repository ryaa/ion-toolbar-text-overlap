# Prerequisities

* [Node.js](http://nodejs.org/) - install the latest LTS node version  
* [Ionic CLI](http://ionicframework.com/docs/cli/install.html) - install the latest stable ionic cli version  
* Install Capacitor Required Dependencies for iOS and Android Development (see https://capacitor.ionicframework.com/docs/getting-started/dependencies/)

# Instructions
## Initial setup
1. clone the source code repository
2. change to project repository directory (the directory where you cloned the repo)
3. execute the command `npm install`   
4. to build and run the app:  
   * on the desktop:   
      - execute the command `ionic serve` or `npm run serve` to build and run in the local browser   
   * on a real device or a simulator:   
      - execute the command `ionic capacitor build android` or `ionic capacitor build ios` to open projects in Android Studio or XCode, then build from there
