# internet_connectivity_checker

Easy way to check internet connectivity in Flutter.

## The idea used in brief:

A stream is being created which would constantly check if the app is able to get connected to google.com. This stream is being used in a StreamBuilder.

## Drawbacks

If Google goes down, the internet connectivity will always be "NOT_CONNECTED"
