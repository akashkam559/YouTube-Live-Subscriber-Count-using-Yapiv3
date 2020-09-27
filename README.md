# YouTube-Live-Subscriber-Count
YouTube Live Subscriber Count, fetch YouTube analytics API from Google developers console and show real time live YouTube subscribe count.

Demo
------
![YouTube Live Subs  Count  (1)](https://user-images.githubusercontent.com/41515202/94376074-d8600d00-0135-11eb-86f0-0b3f00312463.png)

![YouTube Live Subs  Count  (2)](https://user-images.githubusercontent.com/41515202/94376075-d9913a00-0135-11eb-8ecc-e2ccfe9e0d83.png)

![YouTube Live Subs  Count  (3)](https://user-images.githubusercontent.com/41515202/94376078-da29d080-0135-11eb-9886-06eb3b38b80f.png)

![YouTube Live Subs  Count  (4)](https://user-images.githubusercontent.com/41515202/94376079-db5afd80-0135-11eb-93de-9df543da9e84.png)

![YouTube Live Subs  Count  (5)](https://user-images.githubusercontent.com/41515202/94376082-df871b00-0135-11eb-9a10-a7889bb89f78.png)

![YouTube Live Subs  Count  (6)](https://user-images.githubusercontent.com/41515202/94376084-e2820b80-0135-11eb-9cfd-6ad489b3a674.png)

What is it ??
--------------
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


OUTPUT
------------



