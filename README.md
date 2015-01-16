#Twitter Application-only Authentication (OAuth) using Python
Provides a set of functions to allow authentication via Twitter's Application-only authentication protocol.
Methods include the following:
 * getting bearer token
 * invalidating bearer token
 * simple search function

If you wish to use this script you will have to have registered your application with Twitter via dev.twitter.com
Then modify the following lines:

```python
consumer_key = 'c' # put your apps consumer key here
consumer_secret = 'd' # put your apps consumer secret here
```

At the bottom of the script you will see a demo of getting a bearer token, using the bearer token to perform a search
and then invalidating the token.

## Notice
This code is not tested and probably shouldn't be put into production systems, and is only supposed to reperesent the steps involved in performing application-only authentication. It is really really quickly and dirtly mocked up.

It also includes a bunch for rubbish at the bottom which I will clean up shortly

## Contact Me
If you have any problems contact me via twitter @jonhurlock

