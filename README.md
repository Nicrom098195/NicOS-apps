# NicOS-apps

[NicOS](https://nicos.nicromcampe.repl.co) is a small web-based os that I've developed on [replit](https://repl.it).

You can install applications in NicOS in this way:

## 1. Open the package installer

Go on [NicOS](https://nicos.nicromcampe.repl.co) and open the package installer

![Package installer](https://i.imgur.com/S5jZNd8.png)

## 2. Paste the application URL

Every NicOS app has an URL to a json file with the app's information.
Paste the URL to the json file in the input field

![GUI](https://i.imgur.com/6siQikO.png)

## 3. Install

After pasting the URL of the app, install that clicking the **Install** button

![Install button](https://i.imgur.com/u0mInS1.png)

Then should appear a notification showing that the app has been installed successfully

# Developing an application

Everyone can develope a NicOS application, the requirements are:
- Knowing a little of HTML, CSS and JavaScript
- A text editor
- An internet connection
- [Font Awesome icons v4.7](https://fontawesome.com/v4/icons/)

Let's start with the developing of the app

We nedd to create a json file for the app to work, this will be our only file.
In the file, let's put a basic code:<br>
```{"name":"","icon":fa-","code":""}```<br>
This is the basic json file of the app, now you have to chose:
- a name for the app (to put after the **"name"** key)
- an icon for the app (you will need to get the icon code from [Font Awesome v4.7](https://fontawesome.com/v4/icons/)
- some HTML, CSS and JS code to put in the **"code"** key

I suggest you to use an **<iframe>** tag for the code, and inserting the webpage you want to see.

The final result should be like [this](https://github.com/Nicrom098195/NicOS-apps/blob/main/apps/demo_app/app.json)
 
After this, you must to upload the file onlino to any hosting like [Pastebin](https://pastebin.com/) or [GitHub](https://github.com/), and to paste the URL of the file in the Packages installer.
Now you have a basic NicOS app, and you can do now any application you want, your fantasy is the only limit.

 
 ## Note
 
 you can use the **notification** function to show notifications with:
 ```notification(title,text,emergency[true|false])```<br>For example:<br>```notification("Virus detected","There is a virus in your device",true)```<br>will show this:<br>![Emergency notification](https://i.imgur.com/xCyf5e6.png)<br>Or this:<br>```notification("Welcome to NicOS","Welcome to NicOS, the web-based OS")```<br>will show:<br>![Normal notification](https://i.imgur.com/0kPpDc6.png)
