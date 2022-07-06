# python async vs sync https get demo
Tests how much faster it is to make https get requests with python when doing async vs sync requests
### example results:
```
    $ python3 make_async_requests.py 10_urls.csv
    The sync-requests/ directory was created!
    The async-requests/ directory was created!
    making synchronous requests...
    get https://www.google.com request response saved in sync-requests/1657132366.811193_aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbQ==
    get https://www.plus.google.com request response saved in sync-requests/1657132367.961231_aHR0cHM6Ly93d3cucGx1cy5nb29nbGUuY29t
    get https://www.youtube.com request response saved in sync-requests/1657132368.5839438_aHR0cHM6Ly93d3cueW91dHViZS5jb20=
    get https://www.facebook.com request response saved in sync-requests/1657132368.800961_aHR0cHM6Ly93d3cuZmFjZWJvb2suY29t
    get https://www.instagram.com request response saved in sync-requests/1657132369.4767401_aHR0cHM6Ly93d3cuaW5zdGFncmFtLmNvbQ==
    get https://www.twitter.com request response saved in sync-requests/1657132370.003985_aHR0cHM6Ly93d3cudHdpdHRlci5jb20=
    get https://www.gmail.com request response saved in sync-requests/1657132371.953959_aHR0cHM6Ly93d3cuZ21haWwuY29t
    get https://www.ebay.com request response saved in sync-requests/1657132372.6347709_aHR0cHM6Ly93d3cuZWJheS5jb20=
    get https://www.linkedin.com request response saved in sync-requests/1657132372.983913_aHR0cHM6Ly93d3cubGlua2VkaW4uY29t
    get https://www.apple.com request response saved in sync-requests/1657132373.471808_aHR0cHM6Ly93d3cuYXBwbGUuY29t
    For 10 sync requests it took 7.031887769699097
    making asynchronous requests...
    get https://www.apple.com request response saved in async-requests/1657132373.614781_aHR0cHM6Ly93d3cuYXBwbGUuY29t
    get https://www.facebook.com request response saved in async-requests/1657132373.652744_aHR0cHM6Ly93d3cuZmFjZWJvb2suY29t
    get https://www.instagram.com request response saved in async-requests/1657132373.694653_aHR0cHM6Ly93d3cuaW5zdGFncmFtLmNvbQ==
    get https://www.linkedin.com request response saved in async-requests/1657132373.759725_aHR0cHM6Ly93d3cubGlua2VkaW4uY29t
    get https://www.google.com request response saved in async-requests/1657132373.8172119_aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbQ==
    get https://www.youtube.com request response saved in async-requests/1657132373.9874618_aHR0cHM6Ly93d3cueW91dHViZS5jb20=
    get https://www.ebay.com request response saved in async-requests/1657132374.1642072_aHR0cHM6Ly93d3cuZWJheS5jb20=
    get https://www.twitter.com request response saved in async-requests/1657132374.2042198_aHR0cHM6Ly93d3cudHdpdHRlci5jb20=
    get https://www.plus.google.com request response saved in async-requests/1657132374.493839_aHR0cHM6Ly93d3cucGx1cy5nb29nbGUuY29t
    get https://www.gmail.com request response saved in async-requests/1657132374.98636_aHR0cHM6Ly93d3cuZ21haWwuY29t
```
