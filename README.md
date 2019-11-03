# Riru - Clipboard Whitelist

A module of [Riru](https://github.com/RikkaApps/Riru). Allow specific application access clipboard in background on Android 10.

## Requirements

* [Riru](https://github.com/RikkaApps/Riru) > 19 installed.
* Android 10



## Configure


* Add package to whitelist  
  Edit file `/data/misc/riru/modules/clipboard_whitelist/packages.list` and add package name you want
  
* Check module injected  
  Open terminal and type
  ```bash
  getprop sys.clipboard.whitelist
  ```

## Build

1. Install JDK, Android SDK, Android NDK

2. Configure local.properties 

   ```properties
   ndk.dir=/path/to/android/ndk
   sdk.dir=/path/to/android/sdk
   cmake.dir=/path/to/android/cmake/*version*
   ```

3. Run command 

    ``` bash 
    ./gradlew build
    ```
    
4. Get riru-clipboard-whitelist.zip in module/build/outputs



## Feedback

Telegram Group [Kr328 Riru Modules](https://t.me/kr328_riru_modules)