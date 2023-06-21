# Change the brightness of the lights depending on the sentiment of the news
This script uses the [newsAPI](https://newsapi.org/) to get the top headlines and then uses 
[openAI](https://beta.openai.com/) to get the sentiment of the headlines. 
The script then changes the brightness of the [lifx](https://www.lifx.com/) lights depending on the sentiment of the news.

## Table of Contents
* [How to use](#how-to-use)
* [Credits](#credits)

## How to use
1. Create a lifx account and get your token from [here](https://cloud.lifx.com/settings)
2. Create an openAI account and get your token from [here](https://beta.openai.com/account/api-keys)
3. Create a newsAPI account and get your token from [here](https://newsapi.org/register)
4. Clone the repo
```sh
git clone https://github.com/catbox-dev/newsMoodLight.git
```
5. Install the requirements
```sh
pip3 install -r requirements.txt
```
6. Replace the tokens in confi.ini with your tokens
7. Run the script
```sh
python3 newsMoodLight.py
```

## Credits
* [newsAPI](https://newsapi.org/)
* [openAI](https://beta.openai.com/)
* [lifx](https://www.lifx.com/)
* Project by [catbox-dev](https://github.com/catbox-dev)