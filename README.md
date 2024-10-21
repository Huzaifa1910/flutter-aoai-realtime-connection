# dart_aoai_rt_connection

A 

## Getting Started



This project is a starting point for a Flutter application.
.

:
### Steps to Run the Application

-


1. **Clone the Repository**: Clone this repository to your local machine.

[on    ```bash

samp    git clone <repository-url>

    ```

2. **Install Dependencies**: Navigate to the project directory and run the following command to install the required dependencies.

   
    flutt
    ```


er pu
3

    <u
 

    ``

4
    ``




    





   






- 







-


For help getting started with Flutter development, view the [online documentation](https://docs.flutter.dev/), which offers tutorials, samples, guidance on mobile development, and a full API reference.
 [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)

A few resources to get you started if this is your first Flutter project:

### Additional Resources
Use the **Stop Recording** button to process the recorded audio.
- Use the **Start Recording** button to begin recording audio.
- Once the application is running successfully, you will see a screen where the session will automatically start.

### Using the Application
 ```
    flutter run
    ```bash
5. **Run the Application**: Use the following command to run the application.
```
      'wss://<endpoint-url>/openai/realtime?api-version=2024-10-01-preview&deployment=<deployment-name>&api-key=<api-key>');
    _channel = IOWebSocketChannel.connect(
`dart
. **Configure WebSocket**: Replace the placeholders in the WebSocket URL with the required variables such as endpoint, deployment name, and API key.

`
    <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
   <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
ses-permission android:name="android.permission.RECORD_AUDIO"/>
    ```xml
. **Set Permissions**: Ensure that you have assigned the necessary permissions in the `AndroidManifest.xml` file for storage and microphone access.
b get
 ```bash
