# AutoTweet

# Installation instructions

You need Python on your machine. Firstly you need to install the Tweepy library:

```
./setup.sh
```

Next you need to create a Twitter application. Visit:

http://twitter.com/oauth_clients

in your web browser and click "Register a new application".

Then you can edit your "register.py" script, entering the consumer key and consumer secret into the placeholders in the code. Then run the registration script (once only)

```
./register.py
```

Visit the URL that the script outputs. Paste the PIN that the URL generates into the command-line script.

Edit your "tweet.py" entering the access tokens from the Twitter website. N.B. the access tokens must be read/write tokens, otherwise they will not be able to write data to Twitter.

Now you can run:

```
./tweet.py 'I am tweeting from the command-line'
```

If you like, you can copy tweet.py to somewhere in the path e.g.

```
cp tweet.py /usr/bin/tweet
```

then you can tweet from anywhere e.g.

```
tweet 'hello'
```
