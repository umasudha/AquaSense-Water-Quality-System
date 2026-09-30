 Aqua Sense
Is your water safe? Find out in seconds, even with no internet.

Aqua Sense is a water quality testing web app I built for villages, schools and small farms. You type in your readings and it tells you if the water is safe, what is wrong with it, and how to fix it.

Track: Sustainability | Code for Communities Hackathon, Build with AI India
 Live demo: https://aquasense-water-quality-system.netlify.app/

Made by Roahit

Why I built this
Most people cannot tell if their water is safe.

In many villages and small towns, the nearest lab is far away and testing costs money. Results take days. By then, families may have already been drinking that water for a week.

I live in Tamil Nadu and I have seen how rivers like the Vaigai get polluted by sewage and waste. I wanted something anyone could use on a phone, without waiting for a lab.

What it does
You enter the readings. It does the thinking.

Type in values from test strips or a meter, like TDS, pH, turbidity and temperature (up to 45 inputs). Aqua Sense then gives you:

A water quality score and a clear safe, moderate or unsafe result
Risk alerts when something crosses the WHO limit
BOD and COD estimates when you do not have lab values
Scaling and corrosion risk, and irrigation suitability (SAR)
Treatment suggestions based on your own numbers
An offline chat assistant that answers water questions (1000+ topics)
A history page to save samples and compare them later
Light and dark mode
How it works
No black box. Every result comes from a formula you can trace.
The water quality score uses a WHO weighted index
BOD and COD estimates were tuned on CPCB 2019 data from six Indian rivers
Scaling and corrosion use a Langelier style saturation check
Irrigation suitability uses SAR

Everything runs in your browser with plain HTML, CSS and JavaScript (Chart.js for the charts). Your samples are saved on your own device. There is no account to make, no server, and no API keys.

I tested it with a real water sample from the Vaigai River in Tamil Nadu.

Architecture
User on phone or PC
Aqua Sense web appstatic page on Netlify
Formula engine in thebrowserWQI, BOD/COD, LSI, SAR
Score, alerts, treatment,chat
Local storagesample history

The app is one static page. All the calculations happen on the user's device, so it keeps working with no internet and no data is sent anywhere.

Run it yourself
Download or clone this repo
Open index.html in any browser

That is it. No install, no setup. To put it online, upload index.html to any static host.

Project files
index.html is the whole app
README.md is this file
LICENSE is the MIT license
.gitignore keeps keys and local files out of the repo
What I want to build next
A phone app that reads test strips with the camera
One handheld probe with all the sensors in a single device
More languages like Tamil and Hindi
Real lab and CPCB station data to test the formulas better
Limits (please read)
Aqua Sense is a first check. It does not replace a certified lab.

BOD and COD are estimates when lab values are not entered, and they were tuned on a small number of river samples. If the result says unsafe, please get the water tested properly.

Research

A research paper on this project has been submitted to a journal and is under review.

Copyright (c) 2026 Roahit
