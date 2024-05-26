Resut of working with this project it's 
1.Analyze all properties and their purpose in the manifest file:
1. **name**: 
   - **Value**: "Instagram sa Pwa for students ZIEIT"
   - **Purpose**: The full name of your application. This name is displayed when the PWA is installed on a device and in other user interfaces, such as the app manager.

2. **short_name**: 
   - **Value**: "PWA-ZIEIT"
   - **Purpose**: The short name of your application. Used when the app name needs to be shown in a limited space, such as on the home screen.

3. **icons**: 
   - **Value**: An array of objects, each describing an app icon.
   - **Purpose**: Specifies the icons to be used when the app is installed on a device. Different icon sizes ensure proper display on various devices and screens.
   - **Properties of each icon**:
     - **src**: The path to the icon file.
     - **type**: The MIME type of the icon, usually "image/png".
     - **sizes**: The size of the icon in pixels (width x height).

4. **start_url**: 
   - **Value**: "/index.html"
   - **Purpose**: The URL that your application will start from after installation. Typically, this is the main page of your app.

5. **scope**: 
   - **Value**: "."
   - **Purpose**: Defines the scope of the applications that will be controlled by your service worker. In this case, it's everything in the root directory.

6. **display**: 
   - **Value**: "standalone"
   - **Purpose**: Indicates how your application will be displayed to the user. Possible values:
     - **fullscreen**: The app occupies the entire screen.
     - **standalone**: The app looks like a native app, without visible browser elements.
     - **minimal-ui**: Minimal browser user interface.
     - **browser**: The app opens like a regular website in a browser.

7. **orientation**: 
   - **Value**: "portrait-primary"
   - **Purpose**: Specifies the preferred orientation for your application. In this case, it is portrait orientation.

8. **background_color**: 
   - **Value**: "#fff"
   - **Purpose**: The background color displayed while your application is loading.

9. **theme_color**: 
   - **Value**: "#3f51b5"
   - **Purpose**: The theme color of your application. This can affect the color of the browser's address bar and other UI elements.

10. **description**: 
    - **Value**: "A simple Instagram Clone, implementing a lot of PWA for students ZIEIT"
    - **Purpose**: A brief description of your application. Used to provide information to users and for SEO.

11. **dir**: 
    - **Value**: "ltr"
    - **Purpose**: Indicates the text direction in the application. In this case, the text will be displayed from left to right.

12. **lang**: 
    - **Value**: "en-US"
    - **Purpose**: Specifies the language of the application. In this case, it is English (US).

Linking the manifest file informs the browser about the existence of the PWA and how to properly handle it.
