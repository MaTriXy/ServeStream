Compiling
---------

Note: The build instructions and scripts assume you are running Unix or Linux.

1.) To compile ServeStream using Ant, you must specify where your Android SDK and NDK are located via the local.properties file. To generate a local.properties file run the following command from the root directory: 

android update project --path .

2.) Insert two lines into the local.properties file with the full path to your SDK and NDK, for example:

sdk.dir=/home/user/Android/adt-bundle-linux/sdk
ndk.dir=/home/user/Android/android-ndk-r8c

3.) Finally, from the project root run the following command to build the application:

ant clean debug

Privacy
-------

ServeStream does not collect or share any user data.
