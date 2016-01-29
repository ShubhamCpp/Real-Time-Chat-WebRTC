# Real-Time-Chat-WebRTC
A Cross Platform Web Chatting Application through your Browser made with WebRTc Javascript APIs
It implements Peer to Peer Video Chat with Node.js and Socket.io. It is similar to the Websockets approach, but a little different.

## Inspiration

The most frequently used application for connecting and doing Live Video Chat is Skype. However, I always had some or the other problem with Skype. Sometimes it had to be updated, other times the other person's app had some issue and the rest of the times, well I didn't have Skype installed.

So, Skype didn't so work out for me. Now what?

Well, I heard there's this new thing out there called WebRTC that let's you do Video Chatting through the Browser.
That means no Application wanting to be installed,updated and logged onto.

Yes. Yes, you heard it correctly. The icing on the cake, it's completely Open Source.

## What is WebRTC ?

WebRTC is a free, open project that provides browsers and mobile applications with Real-Time Communications (RTC) capabilities via simple APIs.

Yes, Javascript APIs that let you connect Peer to Peer and exchange Video information.
For more details see this Google video :- [Google I/O 2013 WebRTC](https://youtu.be/p2HzZkd2A40)

# Setting it Up

### Cloning this Repository onto your Computer(Linux)

To install git:

    opkg install git

Then clone this repository using `git clone <git repo URL>`.

### Cloning this Repository onto your Computer(Windows)

1. Just download it as zip.
2. Extract to the Specified Folder.

### Setting up a Server

1. Make sure you have node.js installed on your Computer. If not download and install from :- [Node.js Download](https://nodejs.org/en/download/)
2. Using the Command Prompt in Windows or Terminal in Linux or MacOS :

` node server.js `

3. This will make a local https Server.

Note :- WebRTC now works only on HTTPS. HTTP is no longer supported.
The Certificates are in the HTTPS_Permissions Folder. However, these are not fully supported. 
You will be able to host the Server. However, the Browser will give you a Warning saying that the Certificates are invalid.
Proceed if you are on LAN and testing it out.
For Web Hosting please buy a proper https domain.

### Video Chatting

1. Once the Server is up and running, Go to your https://ip@port 3000.
In my case :- https://192.168.1.12:3000 (http will not work)
If you are on the PC where the Server is hosted you can also visit :- https://127.0.0.1:3000
Note: You might get the Invalid Certificate Warning I talked about earlier. Just Proceed if you're just testing it out or are on LAN.

2. Enter your Name.

3. Enter your Room Name.

4. Go to another Browser on your PC or any other PC or device on the same Local Area Network(i.e., connected to the same Wifi,etc.) and open the same page. 
Note: You might get the Invalid Certificate Warning I talked about earlier. Just Proceed if you're just testing it out or are on LAN.

5. Enter another Name.

6. Enter the Same Room Name.

7. You will be asked for Webcam and Microphone Permissions. Give the Permissions to access the Video Chat.

8. Enjoy

# Author

- Shubham Chopra 

    Github Link :- [ShubhamCpp](https://github.com/ShubhamCpp)

## Contact

For any further queries contact me on my email :- shubham.chopra2906@gmail.com

Also, Feel Free to commit, very much Appreciated.

## License

This bundle is dual-licensed under MIT and GPL licenses.

* [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)
* [http://www.gnu.org/licenses/gpl.html](http://www.gnu.org/licenses/gpl.html)

Use it, change it, fork it, sell it. Do whatever you want, but please leave the author attribution.
 
