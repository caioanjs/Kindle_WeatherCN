# Kindle_WeatherCN
Kindle WeatherCN, Chinese calendar system
Principle: Built-in browser accesses H5 page

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/00-JustSoso.jpg)

# Important First Step: Turn Off Screen Sleep Mode
Click the magnifying glass, type in the search box: ~ds and press Enter

Operation reference: https://bookfere.com/post/150.html


# Method One: Access Public Website
## Test Site
The 2025 version has fixed: the Kindle's inaccurate local clock issue. The program will actively sync the correct time from the internet every 30 minutes.

Direct access => https://kw6.netlify.app

Custom settings: Click the "City" on the page to enter custom parameter settings. After clicking save, a configuration URL will be generated. Just save this URL.

Backup sites:

Test site: https://0111.github.io/Kindle_WeatherCN

Test site: https://0111.github.io/Kindle_WeatherCN/config.html

Chrome simulates a 600*700 display (roughly matches Kindle 7th Gen)

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/05-Chome_WebView.png)


# Method Two: Host Your Own Server
## Step One: Download and extract the Kindle_WeatherCN script

## Step Two: Deploy the www directory to your web server

## Step Three: Visit http://website using the native Kindle browser
![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/03-WebVist_127-0-0-2.png)

## Step Four: Customize your city setting
Visit the page http://website/config.html

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/04-Setting_City.png)

After correct configuration, choose “Apply Configuration”

Once the new page loads, save it as a bookmark.
