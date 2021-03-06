# Agora Real Time Messaging SDK for Unity
A Unity SDK including a sample app to show Login /Logout, Log in to/out of channel, Get Channel Member Count, Send/Receive Channel Message, Send Peer Message, Query Member, and token Authentication

*其他语言版本： [简体中文](README.zh.md)*

The Agora Unity3D Sample App is an open-source demo that will help you get message chat integrated directly into your Unity3D applications using the Agora RTM SDK.

With this sample app, you can:

- Login into RTM Server
- Send point to point message and receive point to point message off line
- Display point to point history message
- Join channel
- Send channel message, receive channel message
- Get channel member count
- Query a member in the channel
- Leave channel
- Logout RTM server
- Token Authentication

## Developer Environment Requirements
- Unity3d 2017 or above
- Real devices (Windows, Android, iOS, and Mac supported)
- Some simulators are function missing or have performance issue, so real device is the best choice

## Quick Start

This section shows you how to prepare, build, and run the sample application.

### Obtain an App ID

To build and run the sample application, get an App ID:
1. Create a developer account at [agora.io](https://dashboard.agora.io/signin/). Once you finish the signup process, you will be redirected to the Dashboard.
2. Navigate in Agora Console on the left to **Projects** > **More** > **Create** > **Create New Project**.
3. Save the **App ID** from the Dashboard for later use.

### Run the Application   

1. First clone or download this repository (the package can also be downloaded directly from this link: https://bit.ly/3grvN9C)
2. Open **Assets** > **Scenes** > **MainScene.unity** in your Unity3D Editor
3. Next go into your Heirarchy window and select **MessengerManager**, in the Inspector add your **App ID** to to the **AppID** Input field

#### Test in Editor 
1. Go to **File** > **Builds** > **Platform** and select either Windows or Mac depending on the device you are working on. 
2. Press the Unity Play button to run the example scene 

#### Deploy to Windows, Mac, Android
1. Deploy to Mac, Android, and Windows by simply changing the Platform in the **File** > **Build Settings**, then switch to your prefered platform
2. Hit **Build and Run**

#### Deploy to iOS
1. Change Platform to iOS in the Platform in the **File** > **Build Settings** Window, hit **Build And Run**
2. In Xcode under the **General** Tab, under **Targets** > **Unity-iPhone**> **Frameworks, Libaries, and Embedded Content** change **AgoraRtmIos.framework** to **Embed & Sign**
3. Press the Play button in Xcode to build to your device

Example exported XCode setting (Unity 2017,2018)
![rtm2018-sign](https://user-images.githubusercontent.com/1261195/90598897-c68b6180-e1a8-11ea-841c-12d06cf635d2.png)

Example exported XCode setting (Unity 2019.3)
![rtm2019-sign](https://user-images.githubusercontent.com/1261195/90599047-05211c00-e1a9-11ea-9b2b-ac8114101a0d.png)
If the two Agora frameworks did not show up in the list, drag them from project file tree over.

Here is a video recording to show iOS build working,  [link to video](https://bit.ly/3aWvPEa)

## Resources

- For potential issues, take a look at our [FAQ](https://docs.agora.io/en/faq) first
- Dive into [Agora SDK Samples](https://github.com/AgoraIO) to see more tutorials
- Take a look at [Agora Use Case](https://github.com/AgoraIO-usecase) for more complicated real use case
- Repositories managed by developer communities can be found at [Agora Community](https://github.com/AgoraIO-Community)
- You can find full API documentation by running the index.html file found at Unity-RTM/Docs/html/index.html from your file explorer
- If you encounter problems during integration, you can ask question in [Stack Overflow](https://stackoverflow.com/questions/tagged/agora.io)
- You can file bugs about this sample at [issue](https://github.com/jakep84/Unity-RTM/issues)

## License
The MIT License (MIT).
