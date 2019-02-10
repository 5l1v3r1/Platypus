# Platypus

![image](https://i.imgur.com/lfGuoQE.png)

Project Platypus is a tool that will allow you to input a city name and receive a variety of geolocated OSINT exported as a CSV.  Platypus will us MapQuest API, allowing you to pull construction, traffic, and other road advisories.  It will also, in the future, incorporate some web scraping to collect protest locations where available.  The purpose of this tool is for travel security. Use it to streamline your OSINT collection for travel reports, personal or professional.

# How-to
Edit `platypus.py` and place your API key in the `key` variable.
Run `python3 platypus.py`, specify the file which read the entries from and then specify the file which save the results to.

# Example

An input file must be formatted as `City,State`. For example `New York,NY` and `Dallas,TX`.