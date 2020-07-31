# Meme-to-CC
    
# Summary 
  Grab memes from a subreddit for memes, I will use r/highqualitymemes, and send them to a google photos folder for
  a chromecast to use as wallpapers for a TV. This is a very basic python3 script intended for individual home use. 
  - USES: Reddit API, Google Photos API, python3+. 

# Pre-Req
  - change 'redditAPI.txt' values to match your own
  - download your google photos API key json file and put it in the project directory
  - install python3
  - install pip
  - install Pillow:
    - `pip install Pillow`
  - install praw:
    - `pip install praw`
  - install pandas:
    - `pip install pandas`

# Run
    python3 forreddit_to_cast.py -s memes -l 20
    or
    python3 forreddit_to_cast.py
  - arguments: 
    - --sub or -s: for choosing your sub. ex memes or highqualitymemes
    - --limit or -l: for choosing the limit of images that are downloaded ex 10,20,30,50,100
