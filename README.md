# HomeSharp
HomeSharp aims to create a platform for bringing a variety of different home automation control systems into one. Making it possible for a user to handle, and control all
the smart devices from one GUI, using a smart API translating all the different requests to the specific standard used by the manufacturer (Eg. Netatmo, Telldus, Philips Hue).

## Getting started
Getting started with HomeSharp is easy! All you have to do is change some user specific settings, install a few components, and you're ready to go. Just follow the steps below and
you'll be running HomeSharp in a matter of minutes.

1. Install Node.js - follow the instrucitons at: http://nodejs.org/
2. Install Mongo DB - follow the instructions at: http://www.mongodb.org/
3. Install the Iris API component - follow the instructions at: https://github.com/HomeSharp/Iris
4. Install the Quartz GUI component - follow the instructions at: https://github.com/HomeSharp/Quartz
5. Run Iris
6. In the Quartz dir, find the confi(this is not fixed yet...)
7. Run Quartz
8. Navigate to http://127.0.0.1:8080 or http://localhost:8080
9. Create a new account and login
10. HomeSharp is now up and running and you're ready to start connecting your devices!

## Connecting your devices
Once HomeSharp is up and running and your user account is created, it's time to actually start connecting your devices to HomeSharp!
This is a very easy process, though it varies some depending on the manufacturers devices being connected to Quartz, the example below is taking you through
the process of adding Netatmo devices. A process used and similar when adding a lot of other manufacturers devices.

1. Locate the TODO
