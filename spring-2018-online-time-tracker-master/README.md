# Otter
## Online Time Tracker

## Team/Contributors
1. [Zachary Kimelheim](https://github.com/zackkimelheim)  :bowtie:
2. [Imtiaz Haque](https://github.com/ih646) :princess:
3. [Alex Bae](https://github.com/ajsbae) :construction_worker:
4. [Andrew Huang](https://github.com/anzhe7) :guardsman:

## Project Description
Introducing Otter, a new platform to help you track how much time
you spend online. Information is gathered using a Google Chrome
extension, and then displayed on a beautiful and secure
password-protected website. Know exactly how much time you spend on
your desktop on the Internet. Use this information however you like,
it’s yours to keep!

Check out [Otter](https://otter-.herokuapp.com) now!

## Short History of Our Beginnings
Internet companies often maintain a detailed understanding of our minds.
Google knows what we search. Facebook, Twitter, Instagram, Snapchat,
they know what interests us and with whom we interact. Amazon knows
what we buy. YouTube and Netflix know what we watch. With this
information, Internet companies can choose which information we see in
order to entice us to use their platform more and more. Because of
this, humans spend more and more time online.  We don’t know how much
time we spend online. Maybe if we knew, we could make more conscious
choices about how we spent our time.

## Contributing Information
[Refer to Contributing.md](https://github.com/nyu-software-engineering/online-time-tracker/blob/master/CONTRIBUTING.md)

## Instructions on Building and Testing the Project

To Branch:

0. git pull (if there are changes, it's a good idea to have them) 
1. git branch -b newname 
2. (do stuff and edit stuff)
3. git checkout master (this switches you over to the master branch)
4. git merge newname (this merges newname branch with master)
5. git pull
6. git push origin master

To Deploy Changes on Heroku:
1. (in main directory) git subtree push --prefix myapp heroku master


## Getting Started with the Online Time Tracker 
The Online Time Tracker is an application that gives users statistics on their internet usage. Here are the steps to getting started:
1. Download the folder named "spring-2018-online-time-tracker-master". Once downloaded,  move this file to the desired location within your computer. 
2. Open Google Chrome and click on the **Settings**. Within **Settings** should be an option named **Extensions**
3. Within **Extensions**, turn on **Developer mode** located on the top right
4. Click **Load Unpacked** in the options that appear
5. In the popup, search through the directory until you reach the **extension** folder. The order should be
**spring-2018-onlilne-time-tracker-master** >  **myapp** >**extension**
6. Online Time Tracker has now been installed and is located on the top right next to the URL bar. 

## Features of Online Time Tracker: 

### Login
The Online Time Tracker allows users to create accounts and login. Creating an account allows users to save their internet usage data.   
![Login](https://i.ibb.co/tPR6f9W/loginsignup.png)


The user can access data and graphs that display his/her accumulated data over the span of 1 month. A valid email must be entered or an error message will popup on the screen. 
![Error](https://i.ibb.co/WFCxcR5/ottors.png)

## Graphs
The Online Time Tracker offers users multiple ways to view their internet usage statistics. The Online Time Tracker gives users the option to view their internet usage in a pie chart, bar chart, and column chart format. These formats allow the user to view his/her data in an easy-to-read, accessible format.

The user can click on the buttons labeled pie chart, bar chart, or column chart to change the graph that appears. Alternatively, the user can click on the chart itself to switch between the three views. 

### Pie Chart: 
![Pie Chart](https://i.ibb.co/Vw8DGm9/chartoptionspie.png)
### Bar Chart: 
![Bar Chart](https://i.ibb.co/wzGjH5n/chartoptionsbar.png)
### Column Chart: 
![Column Chart](https://i.ibb.co/3v0fC6S/chartoptionscolumn.png)

Hovering the cursor over the different sections of the pie, bar, or column chart will display the total number of minutes spent on the site that is represented by that section.
### Chart Time Statistics:
![Mouse Hover](https://i.ibb.co/7X6pB86/chartmouse.png)


## List Format
Aside from the three charts, the user can also view his/her usage statistics 
in a list format that displays each website name, time spent on each website, 
and percentage of the total usage time spent on each website. 
![List View](https://i.ibb.co/k3jBnkS/list-view.png)

## Alarm

One final feature of the Online Time Tracker is the alarm feature. The alarm feature allows the user to put in a desired amount of time. To start the timer, the user must enter the amount of minutes desired and then press start.
![Alarm](https://i.ibb.co/Jr5Q2bC/alarms.png)

Once the user enters in a time and presses start, there will be a real-time 
counter in the format "mm:ss". The user is given the option to resume, pause, restart, or cancel the timer. 
![AlarmTime](https://i.ibb.co/JxM2QCz/alarm.png)

This counter , when it hits 00:00, will alert the user with a 
pop-up that signals that his/her time is up and that he/she should consider 
halting.
![AlarmStop](https://i.ibb.co/rw4LLCB/ottormessagestay.png)


