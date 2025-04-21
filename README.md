# TaskManager

Multi-Platform Application to manage Tasks. With a 3-tier modern architecture to cope with scallability:
 * ApplicationLayer - TaskManagerApp
 * LogicLayer - TaskManagerApi
 * Datalayer - TaskManagerData

Developped in a XAMPP environment with a Apache and a MariaDB deployment.   
Then deployed on InfinityFree servers so that we could run it on a server.

## Application Layer

We will use Apache Cordova to create a multi-platform (iOS/Android/Web) application. Massively using HTML / CSS / JS.

Install Cordova new application.
```
> npm install -g cordova
> cordova create TaskManagerApp
> cd TaskManagerApp
> cordova platform add browser
> cordova platform add ios
> cordova platform add android
```

Cordova build & run iOS simulator.
```
> cordova build ios
> cordova run ios
```

## Logic Layer

## Data Layer
