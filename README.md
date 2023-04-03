This is a facebook chat bot you can easily customize the response. If you think this project is interesting, please give me a star. Thanks.

# Quick Start Guide

## Requirement

- node >= 4.4.1

## Usage

### Start chat bot

- step1: modify `index.js` and change userInfo to your own email and password.

```javascript
var userInfo = {
  email: "Your_Email@test.com",
  password: "Your_Password",
};
```

- step2: start chat bot

```bash
npm start
```

## How to customize your bot

### customize the response

modify the file `database/respond.json`.<br>
The bot will find the "keyword" and make response.

```json
{
  "hello": "Hello ~ I'm Pudding Dog",

  "ya": "YAAAAA~~",

  "apple": "apple is good"
}
```

### customize the default message

modify the arr in `database/question.json`.<br>

```json
["Hello", "Ya", "I love apple"]
```

## How to stop the chat bot

Just terminate the process or say "/stop" to the bot on facebook.<br>
