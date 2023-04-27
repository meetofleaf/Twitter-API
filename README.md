## Twitter Live Streaming Application

This is a Python application that streams live tweets from Twitter based on the given hashtags and users. The application uses the Tweepy library to connect to the Twitter API and retrieve tweets in real-time.

### Prerequisites

To run this application, you will need to have the following:

- Python 3 installed
- Tweepy library installed
- Access to Twitter API credentials

### Installation

1. Clone this repository to your local machine using Git or download the code as a ZIP file.
2. Install the required dependencies by running the following command in your terminal:

```python
pip install tweepy
```

3. Create a Twitter Developer Account to obtain the following credentials:
    - Consumer Key
    - Consumer Secret
    - Access Token
    - Access Token Secret

4. Open the `twitter_credentials.py` file and replace the placeholders with your Twitter API credentials.

```python
# Twitter API credentials
CONSUMER_KEY = 'your_consumer_key'
CONSUMER_SECRET = 'your_consumer_secret'
ACCESS_TOKEN = 'your_access_token'
ACCESS_TOKEN_SECRET = 'your_access_token_secret'
```

5. In the main function of the `twitterwall.py` file, modify the `hash_tag_list` and `users` variables to the desired hashtags and user IDs that you want to stream.

```python
hash_tag_list = ["#tesla", "#elonmusk", "#spacex"]
users = ["123456789"] # user ID of 'meetofleaf'
```

### Usage

To start streaming tweets, run the following command in your terminal:

```python
python twitterwall.py
```

This will connect to the Twitter API and begin streaming live tweets that match the specified hashtags and users. The tweets will be printed to the console in real-time.

### Output

The output of the application will be a live stream of tweets that match the specified hashtags and users. The tweets will be displayed in the following format:

```
Username
----------------------
Tweet text
--------------------------------------------------
```
