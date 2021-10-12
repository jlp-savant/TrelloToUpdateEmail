# Trello Progress Email Creator
This program is designed to create an email file to be sent for progress on a trello board. My boss doesn't like trello and prefers email, so I've developed this software to take the notes from trello and generate an email to his liking form the information on trello

## Setup Instructions
1. Visit [Trello Api Key](https://trello.com/app-key) to get your api key. Add the API key to the config
2. Directly under the api key, there is a generate token, follow the wizard and copy your token into your config
3. Add your username and the board name to the config file

```
{
    "apikey": "your-api-key",
    "apitoken": "your-api-token",
    "boardname": "board-youre-looking-for",
    "username": "your-trello-username"
}

```


## Links
- [Trello API Key](https://trello.com/app-key)
- [Trello API Introduction](https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/)
- [Trello API Reference](https://developer.atlassian.com/cloud/trello/rest/api-group-actions/)