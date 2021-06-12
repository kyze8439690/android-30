# Docker for Android SDK 30

Docker for Android SDK 30 with preinstalled build tools and emulator image

> Edit from [docker-android-sdk/android-30](https://github.com/docker-android-sdk/android-30)

**Installed Packages**
```bash
# sdkmanager --list
  Path                                        | Version      | Description                                | Location
  -------                                     | -------      | -------                                    | -------
  build-tools;30.0.2                          | 30.0.3       | Android SDK Build-Tools 30.0.3             | build-tools/30.0.3/
  cmdline-tools;latest                        | 2.1          | Android SDK Command-line Tools (latest)    | cmdline-tools/latest/
  emulator                                    | 30.1.5       | Android Emulator                           | emulator/
  patcher;v4                                  | 1            | SDK Patch Applier v4                       | patcher/v4/
  platform-tools                              | 30.0.4       | Android SDK Platform-Tools                 | platform-tools/
  platforms;android-30                        | 3            | Android SDK Platform 30                    | platforms/android-30/
  ndk;21.4.7075529                            | 21.4.7075529 | Android NDK                                | ndk/21.4.7075529/
```

**Usage**

- Non-interactive way
  ```bash
  # check installed packages
  $ docker run -it --rm androidsdk/android-30:latest sdkmanager --list
  # You can also run other Android platform tools, which are all added to the PATH environment variable
  ```
