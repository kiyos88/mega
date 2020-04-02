# Quick start

Now that we are  ready to rock we can create our first `mega application`. In this quick start guide we'll create our first mega app (meda mini app) from scratch. It will show how easy it is to get started with Mega.

## Installing Mega cli

Mega can be installed like any other Node module by installing the  [mega-cli](https://www.npmjs.com/package/mega-cli)  package through  [npm](https://www.npmjs.com/) globally.
```
npm install -g mega-cli
```

## Our first app

Now we can create a Mega application with a simple starter content including "how to debug ?" screen with lottie animation ( 😉 ya lottie is supported you can easily render your after effect animation in mega). 

Now on your command line type :

```
mega-cli init
```

and you will be prompted with series of questions

![alt text](https://i.ibb.co/D4rnkFY/Screen-Shot-2020-04-02-at-10-37-22-AM.png "Mega cli screenshot.")

> **Note:**  you can edit any of the fields later in your `manifest.json` file


## Run Run 🏃

first lets change our directory to the newly created project folder

```
cd MyFirstMegaApp
```
then start the metro-bundler with

```
npm start
```
then forward your `8081` port to be your packaging server with [adb](https://developer.android.com/studio/command-line/adb) 

```
adb reverse tcp:8081 tcp:8081
```
> **Note:**  make sure you have [adb](https://developer.android.com/studio/command-line/adb)  installed (we will remove this step so that you dont have to install anything other than mega to run mega 😉) and have active USB connection with your computer

Now we are done with the setup, open your meda app and head to `Me/About/Developer Screen` then enter you app name as `MyFirstMegaApp`

and voila 

![alt text](https://i.ibb.co/DMvP05p/2020-04-02-11-16-58.jpg "Mega start screen.")