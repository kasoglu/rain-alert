# Rain Alert via SMS

A rain alert program reminds you take an umbrella by sending a SMS to your mobile phone when it will rain in the day.

# Installing
Download the [Python 3](https://python.org) installer package from the official website and install it, if not installed previously.

Run the following in the terminal to install the Requests module to get weather data from [Open Weather Map](https://openweathermap.org/).
```
pip install requests
pip install twilio
```

# How to Use?

Download the source code from the repository and run the file just as any other Python script (.py) file.
```
python3 main.py
```
* Note! For the code to work you need to replace all the placeholders with your own details. e.g. account_sid, lat/lon, from/to phone numbers.

Once you replace the own details in the code, run the program.

If in your **lat/lon** shows Rainy 🌧 program will send you a SMS message to take your umbrella.

# Description

To run your program on the cloud follow these instructions below.

* Head over to [Pythonanywhere.com](https://www.pythonanywhere.com) and go ahead to sign up for a new account.
* Now, once you've signed up and signed in then go ahead to add files section.
* We're going to upload files here. Choose the files from your directory and add here. 
* Go to create Bash console and type ```python3 main.py ```
* And your program will run in the background constantly.

# Documentations

* [Latitude&Longitude](https://www.latlong.net)
* [Twilio](http://twilio.com/)
* [Open Weather Map](https://openweathermap.org/)
