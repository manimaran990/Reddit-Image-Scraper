Reddit-Image-Scraper
====================

Choose a reddit user and download each of his or her Imgur submissions to your local hard drive


Example
--------------
```
python imagescraper.py User123 5
```
This command scrapes the last 5 posts of `/u/User123`, detects his Imgur submissions and downloads it to your desktop in a newly created folder called `/User123/`

Setup
--------------
To use this script, you will need the libraries [praw](https://github.com/praw-dev/praw) and [beautifulsoup](http://www.crummy.com/software/BeautifulSoup/). They can be installed by the `pip` command through your command line as follows:
```
$ pip install praw
$ pip install beautifulsoup4
```
As an alternative, you can also use `easy_install`:
```
$ easy_install praw
$ easy_install beautifulsoup4
```
After that, you're good to go!