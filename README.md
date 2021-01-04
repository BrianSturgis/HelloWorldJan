<div align="center">
<img src="https://github.com/BrianSturgis.png" width="200px" height="auto" >
</div>

<p align="center"> Authored by Brian Sturgis</p>

<p align="center">Updated on Dec 7th, 2020</p>


## Detailed Description

This is an currency exchange application that will take in a amount in U.S dollars and convert it into a foriegn currency.  To come to this solution the application will use "exchange rate API" and javascript to provide solutions.

This application is built currently to be displayed in full screen otherwise the UI will not align correctly with the background artwork
## KNOWN BUGS

-  currently this application is having a issue showing errors from a servor and is the top of the list to diagnose as its required for completion.  
-a lot of repeated code. will Consider making 1 function to make the api call, regardless of the currency selected, and 1 call to getRate() for any currency exchanges.  built out long to help me learn it


## Setup/Installation Requirements

## GIT HUB
- repository location (https://github.com/BrianSturgis/week6project
- open through a git termianl or clone editor.
- got to repo location.
- using git commands clone to local repo or click "download" and unpack on machine


## USING THIS APPLICATION
- This app uses node.js. If you do not already have node.js installed, visit https://nodejs.org/en/download/ and install.
- After installing node, navigate to the root directory of the cloned repo and type in "npm install".
- Then type in "npm run build".

If you would like to run the program through the server, you can type "npm run start" which will build the program and launch the preview to the local server.

If you use Jest to run your tests, open your terminal and go to the root of the project directory and type in "npm test".
If you would like to run the program through the server, you can type "npm run start" which will build the program and launch the preview to the local server.

## API IN)
- go to https://www.exchangerate-api.com/
- Type in your email address in the box where it says "Your email address" and click "Get Free Key"
- The prompt will take you to a dashboard that will show you your API Key.
- Copy and Paste into clipboard 
- and follow in the structions below under "How to set up .env file"

## API ERROR CODES
- "unsupported-code" if we don't support the supplied currency code (see supported currencies...).
- "base-code-only-on-pro" if a request to the free.exchangerate-api.com endpoint is for a base code other than USD or EUR.
- "malformed-request" when some part of your request doesn't follow the structure shown above.
- "invalid-key" when your API key is not valid.
- "quota-reached" when your account has reached the the number of requests allowed by your plan.
- "not-available-on-plan" if your plan level doesn't support this type of request.

## Stretch goals
- a user interface
- form inputs to choose specific or mutliple currencies
- improved and animted user interface
  


## Support and contact details
email Brian Sturgis @ <sturujisu@gmail.com>


## TESTS

| CurrencyConverter(); |  |
| ------| -----------|
| test: will make the API call  |                         |
|  
| expect:  | (response).toEqual(200k). |



| getRateUSA(); |  |
| ------| -----------|
| test:   | will recieve {response.conversion_rates.USA} |
| 
| expect:  | (usa 1) .toEqual(usa 1) |


## Technologies Used
* HTML
* CSS
* Bootstrap
* Javascript
* jQuery
* Coffee
* jest
* Babel
* lint
* webpack
  


### License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE..



Copyright (c) 2020 **Brian Micheal Sturgis**
