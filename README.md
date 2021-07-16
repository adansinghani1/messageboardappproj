# MessageBoard App for Mobile App Development
Similar to our previous project FriendlyChat, this app has a login page where you can either register with: First and Last Name, e-Mail, and Password. I logged in with my test account, personal account, and G-Mail account. Everything is tracked with Firebase with each of the posting. I only used one of the MessageBoard forums and that was tracked. All the messages are tracked but for simplicity, I chose to use my gaming forum.

Demo Link: https://youtu.be/UmhUFkBMMzY

![image](https://user-images.githubusercontent.com/60675989/125956715-8f77bec6-7df4-4380-9795-cfe090352867.png) (Splash Screen)
![image](https://user-images.githubusercontent.com/60675989/125956747-5bc57d83-ba32-4719-a0d1-5deddaf4bf49.png) (GitHub)
![image](https://user-images.githubusercontent.com/60675989/125956797-56193776-f3ae-4e74-a7f4-56244b770ab8.png) (Registration Page)
![image](https://user-images.githubusercontent.com/60675989/125956985-d257b676-1497-4c79-a05c-f2bc625d4916.png) ![image](https://user-images.githubusercontent.com/60675989/125957064-e59b2f08-7190-4a22-b51b-42f27f26af1d.png) (Login Page)
![image](https://user-images.githubusercontent.com/60675989/125957135-7a871391-bd27-46a7-8c5f-c851958380db.png) (Threads)
![image](https://user-images.githubusercontent.com/60675989/125958948-f8ea4896-1cb9-430e-8e25-a2dabad416c8.png) (Firebase)


# Instructions to Start the App:  
Download or clone the repository locally onto your hardrive  
Wait for the files to load into directory  
Change file path with the name of your User folder, not mine. (i.e. C:// Users/kash/Documents/messageboardappproj/)  
Build the project  
After it is build, type this command into your terminal "firebase emulators:start --project=demo-friendlychat" (you will be able to see realtime database)  
The command above will use the firbase.json file and start the emulator and will give you a local port whjich you can access the firebase emulator (see status or authentication, cloud messaging, etc.) Once cloned, you should be able to press the play button or go on the "Run" tab on the tool bar and press run 'build-android.app'  
** make sure your gradle is 6.7.1 or change it in the gradle-wrapper.properties to 6.7.1. I had to move the gradle-wrapper-properties file outside in the main messageboardproj folder. **
