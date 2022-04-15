# Web Scraping - Spotify
<p align="center">
  <img width="400" height="300" src="https://storage.googleapis.com/pr-newsroom-wp/1/2018/11/folder_920_201707260845-1.png">
</p>

- Spotify is an audio streaming and media services provider founded on 23 April 2006 by Daniel Ek and Martin Lorentzon. It is one of the largest music streaming service providers, with over 406 million monthly active users, including 180 million paying subscribers, as of December 2021. Spotify offers digital copyright restricted recorded music and podcasts, including more than 82 million songs, from record labels and media companies. As a freemium service, basic features are free with advertisements and limited control, while additional features, such as offline listening and commercial-free listening, are offered via paid subscriptions. Spotify is currently available in 180+ countries, as of October 2021. Users can search for music based on artist, album, or genre, and can create, edit, and share playlists.
- Spotify is available in most of Europe, as well as the Americas and Oceania, with a total availability in 184 markets. The service is available on most devices including Windows, macOS, and Linux computers, iOS and Android smartphones and tablets, smart speakers such as Amazon Echo and Google Home, and digital media players like Roku.
- Unlike physical or download sales, which pay artists a fixed price per song or album sold, Spotify pays royalties based on the number of artist streams as a proportion of total songs streamed. It distributes approximately 70% of its total revenue to rights holders (often record labels), who then pay artists based on individual agreements. According to Ben Sisario of The New York Times, approximately 13,000 out of seven million artists on Spotify generated $50,000 or more in payments in 2020. 


# What is Web Scraping?
Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. Web scraping a web page involves fetching it and extracting from it. Fetching is the downloading of a page (which a browser does when a user views a page). Therefore, web crawling is a main component of web scraping, to fetch pages for later processing. Once fetched, then extraction can take place. The content of a page may be parsed, searched, reformatted, its data copied into a spreadsheet or loaded into a database. Web scrapers typically take something out of a page, to make use of it for another purpose somewhere else. An example would be to find and copy names and telephone numbers, or companies and their URLs, or e-mail addresses to a list (contact scraping).

# Web Scraping Techniques
In general, there are two ways you can do this:
- Manual: a method where you copy data by copy-pasting from a website
- Automatic: a method that uses code, an application, or a browser extension.

Web scraping is now made easier with the help of browser extensions and applications. There are six commonly used web scraping techniques, namely:
1. Copying data manually
2. Using regular expressions
3. HTML parse
4. Analyze DOM
5. Using XPath
6. Using Google Sheets

# Benefits and Problems of Web Scraping
Following are the four main advantages:
1. Getting Leads
2. Comparing Massive Data
3. Optimization of Reviews, Product Pricing and Service
4. Looking for Company Information

Although web scraping is a very helpful technique in extracting site data, there are also problems to its implementation. At least, the following five things you need to remember if you want to do it:
1. No web scraping technique is 100% effective
1. The data obtained is not always neat
1. Understanding of the structure of the website page remains an obligation
1. Your access to a website may be blocked
1. Not all websites are easy to extract data

# About The Project
The main purpose of this project is to gather data from the Spotify platform, starting with the song title, singer, album, pace, and other details about the song now playing. The web scraping procedure from the Spotify platform can be done in a variety of ways; the accompanying file contains specifics on each of [**these methods**](https://github.com/yandaaw/webscrape_spotify/blob/main/Scraping_Spotify_Music.ipynb).

# Built with
- [**pandas**](https://pandas.pydata.org/)
- [**NumPy**](https://numpy.org/)
- [**spotipy**](https://spotipy.readthedocs.io/en/2.19.0/)
- [**Request**](https://docs.python-requests.org/en/latest/)
- [**urllib**](https://docs.python.org/3/library/urllib.html)

# Getting Started
Spotipy is a lightweight Python library for the Spotify Web API. With Spotipy you get full access to all of the music data provided by the Spotify platform. Assuming you set the `SPOTIPY_CLIENT_ID` and `SPOTIPY_CLIENT_SECRET` environment variables. While request allows you to send HTTP/1.1 requests extremely easily. There’s no need to manually add query strings to your URLs, or to form-encode your POST data. Keep-alive and HTTP connection pooling are 100% automatic, thanks to urllib3.

Read more for [**spotipy documentation**](https://spotipy.readthedocs.io/en/2.19.0/) and [**Request documentation**](https://docs.python-requests.org/en/latest/)
### **Prerequisites**
Here is how to run the library used in this project. First Install the list of libraries below on your device or kernel:
- spotipy <br>
  ```
  pip install spotipy
  ```
- urllib3 <br>
  ```
  pip install urllib3
  ```
- request <br>
  ```
  pip install requests
  ```
  
# Acknowledgements
- [**Wikipedia**](https://en.wikipedia.org/wiki/Spotify)
- [**Spotify for Developers**](https://developer.spotify.com/documentation/)
