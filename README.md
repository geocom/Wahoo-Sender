# Wahoo Sender

## About
After waiting for way to long for Wahoo to support sending all notifications to your Wahoo cycle computer I decided to try and role my own solution. The biggest issue I faced was not reading notifications from the system but reverse engineering the Bluetooth stack. If Wahoo wanted to add this to their official app it would be trivial Google has good documentation on how to do so and there is good example code around on the internet.

## Issues & Bugs
This app does not include any code for anything other than sending messages. Phone calls wont work, Sending workouts wont work(that being said you can upload them using the official app first), changing settings cannot be done.
Furthermore there are likely to be bugs or issues.

## Install
You will need to install the application via the APK in releases(https://github.com/geocom/Wahoo-Sender/releases) or by building the code from source. 

You will also need to turn off battery optimisation in order for the app to continue running in the background while you ride.

## Wahoo if your reading this.
Please implement this into the official app. It is something that is desperately needed(Google it). I don't get SMS'es I get messages via web services(Signal, Facebook Messenger etc) just get it done it’s trivial
