# Face Recognition Mobile Application
## How to use the app:
1. Download and install Android Studio from https://developer.android.com/studio.
2. Start Android Studio and click on "Open an existing Android Studio project."
3. Select the root folder of your Android app source code.
4. Connect your Android phone to your computer using a USB cable.
5. Make sure Developer options are enabled on your phone, and enable USB debugging in the Developer options.
6. In Android Studio, click the Run button (the green triangle) to build and run your app.
7. Select your connected phone as the target device, if prompted.
8. Your app should now be installed and running on your phone.

Note: You may need to install the appropriate USB drivers for your phone on your computer. You can usually find these on the manufacturer's website.

## Information about main files:
I have removed irrelevant files for convenience. Some main files are as follows:
1. Activity_main.xml : It specifies the structure and appearance of the screen elements and how they are organized in the screen.
2. file_paths.xml : File paths where the images are stored.
3. MainActivity.java : It represents the main activity of an Android app. Here I have written code to perform tasks such as:
    - Initializing UI elements (e.g., text views, buttons, etc.) defined in the layout file
    - Handling user interactions with the UI (e.g., button clicks)
    - Updating the UI based on user actions or data changes
    - Starting other activities to display additional screens
    - Performing background tasks, such as data processing or network requests
4. Manifest.xml : It acts as the "manifest" of the app, declaring the app's components (such as activities, services, broadcast receivers, and content providers), permissions that the app requires, and other important details about the app.
5. Permissions.xml : This file contain necessary permission to operate the application.

## Pictures of the Application:
### How application looks like in Mobile phone:
![display_pic](https://user-images.githubusercontent.com/61081924/216766695-597b2a25-e465-4425-9520-dbfcf953bc8a.jpeg)
### Two options available: either use camera or choose from gallery.
![options](https://user-images.githubusercontent.com/61081924/216766741-455090f7-169a-425f-b1b1-5bc34df1a59f.jpeg)
### Taking picture from camera:
![capturing_pic](https://user-images.githubusercontent.com/61081924/216766771-78a14d4f-aeac-41cb-a5a7-688aee35bbbd.jpeg)
### After capturing a picture, it is saved in Gallery (Photos). We can select the picture from gallery by choosing an option Gallery.
![select_pic_from_gallery](https://user-images.githubusercontent.com/61081924/216766781-af498600-5f9f-44cb-bd50-e3dd11d418e4.jpeg)
