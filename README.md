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
## Requirements
Python 3.6+
Twitter Developer Account & API credentials
## Contributing
Feel free to open issues or submit pull requests if you'd like to contribute to this project.

## License
This project is licensed under the MIT License.
