# Bangla Twitter Data Collector

A Python package to collect and analyze Bangla tweets from Twitter.

## Features
Fetches tweets in the Bangla language.
Easy-to-use and customizable.
Supports various filters like keywords, date ranges, and more.

``` pip install bangla-twitter-collector ```

## Usage

```
from tweets import get_tweets_context
a=get_tweets_context('জন্য')
print(a[1])
import json
b=json.loads(open('output.json',encoding='utf-8').read())
```

