# YouTube-Live-Subscriber-Count
YouTube Live Subscriber Count, fetch YouTube analytics API from Google developers console and show real time live YouTube subscribe count.

Table of Content
----------------
* Demo
* Overview
* Tech Used
* Features
* Steps/Process
* Future scope of project

Demo
-----
![YouTube Live Subs  Count  (1)](https://user-images.githubusercontent.com/41515202/94376142-515f6480-0136-11eb-8cd7-f8b50f00fa40.png)

![YouTube Live Subs  Count  (2)](https://user-images.githubusercontent.com/41515202/94376144-57554580-0136-11eb-9037-341cd1e91f4d.png)

![YouTube Live Subs  Count  (3)](https://user-images.githubusercontent.com/41515202/94376147-591f0900-0136-11eb-84b5-834c17f7331b.png)

![YouTube Live Subs  Count  (4)](https://user-images.githubusercontent.com/41515202/94376148-5ae8cc80-0136-11eb-9315-133ee82226c9.png)

![YouTube Live Subs  Count  (5)](https://user-images.githubusercontent.com/41515202/94376149-5b816300-0136-11eb-9be2-84c747a16b65.png)

![YouTube Live Subs  Count  (6)](https://user-images.githubusercontent.com/41515202/94376150-5cb29000-0136-11eb-9111-de2ef9c6f55d.png)


Overview / What is it ??
-------------------------
allows you to see the subscriber count of any YouTube user in realtime
shows the live subscriber count of any user on YouTube as accurately as possible
The subscriber count, view count, video count and comment count are all taken directly from Google's infrastructure via the Analytics API
The counts are updated every second and are guaranteed to be accurate.

Tech Used 
--------------
Google Analytics Youtube Api V3 
YouTube Api
Google Analytics Console/api


Features
-----------
* Shows subscription Count of a YouTube channel (updated every second)

* Shows subscribers needed to reach a milestone YouTube subscriber count (updated every second).

* Accepts usernames/YouTube URLs, Channel names, Channel IDs, or any keywords in general; It acts like a YouTube channel search engine.

* Shows additional useful information about the YouTube Channel such as, YouTube Channel names as the user types the name of channel

Steps/ Process
----------------
* Go to https://console.developers.google.com/apis/library

* Log in with your Google account.

* Next to the logo click on 'Project' and 'Create project'. Name it whatever you want and click on 'Create'.

* Wait until the project is created, the page will switch to it by itself, it will take a couple of seconds up to a minute. Once it's done it will be selected next to the logo.

* Once it's created and selected, click on 'Credentials' from the menu on the left.

* Click on 'Create Credentials' and choose 'API Key'. You can restrict it to specific IPs, or types of requests (website, android, ios etc.) if you want, it's safer that way.
 
* Copy your API KEY, you will need this in the script.

* Make a new PHP file on your web server and use the following code, replacing YOUR_CHANNEL_ID and API_KEY with your channel's ID (it's the code at the end of your channel's URL) and the API Key you got in step 7.
RESULT/FEAURES


Future scope of project
-----------------------
Can be more optimized & effient in loading pages quickly

can be designed more better with up-coming new technologies.
