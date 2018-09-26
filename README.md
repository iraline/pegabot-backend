# spottingbot
Analyzing profile on Twitter for detect behavior of spamming bot

## Installation:

`npm install`

## Usage:

### Command-line interface

Create a `.twitter.json` file that contains:

```json
{
  "twitter_consumer_key": "Your application consumer key",
  "twitter_consumer_secret": "Your application consumer secret",
  "twitter_access_token_key": "Your application access token key",
  "twitter_access_token_secret": "Your application access token secret"
}
```

Then

`npm start username`

or

`source/cli.js username`

*`username` have to be replaced by the profile to analyze*

#### Install bin locally on your system

`npm link`

Then

`spottingbot username`
