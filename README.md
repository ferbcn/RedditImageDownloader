# Reddit Image Downloader Python3

A reddit application that downloads pictures and gifs from a given subreddit.

Changes: 
- requires python3
- files are saved in a specific "subreddit" folder
- files are named according to submission title

# Setup 
1. Create a [reddit personal use script application](https://www.reddit.com/prefs/apps/).

2. Add a `config.py` file to your working directory and add your applications credentials.

		client_id='YOUR_ID'  
		secret='YOUR_SECRET'  
		password='YOUR_PASSWORD'  
		agent='Example Bot by /u/example_bot'  
		username='YOUR_USERNAME'  

3. Run `pip install -r requirements.txt`

# Usage


	Usage: download_images.py [-s SUBREDDIT] [-n NUMBER OF PICTURES] [-p PAGE] [-q SEARCH QUERY] 

	-h --help                           show this
	-s --subreddit SUBREDDIT            specify subreddit
	-n --number NUMBER OF PICTURES      specify number of pictures to download [default: 20]
	-p --page PAGE                      hot, top, controversial, new, rising [default: hot]
	-q --query SEARCH QUERY             specify a specific search term


Your images will appear in the "images/[SUBREDDIT]" folder created by the application.

__Helpful note:__ To view .gif files on a Mac select the image(s) and press "cmd" + "y".


