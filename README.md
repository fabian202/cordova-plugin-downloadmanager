# cordova-plugin-downloadmanager
A Cordova plugin to download file in system's default download manager

## Supported Platforms

 - Android (SDK >= 11)

 ## Installation

 ```
 cordova plugin add https://github.com/fabian202/cordova-plugin-downloadmanager
 ```

 ## How to Use 

 ```
 //once device is ready
var fail = function (message) {    
    alert(message)
}
var success = function (data) {
        console.log("succes");
}
cordova.plugins.DownloadManager.download("Your URL to download", success, fail);
 ```

 ```
Entra a la carpeta de android
Y busca este archivo
project.properties
com.android.support:support-v4:+
Remplazala por esta
com.android.support:support-v4:27.1.0
 ```

## Result

![screenshot](./screenshot/downloadplugin.gif)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
