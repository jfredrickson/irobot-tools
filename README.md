# iRobot Tools

## Setup

```bash
npm install
```

## Usage

You will need your Roomba's IP address as well as its [blid and password](https://github.com/koalazak/dorita980#how-to-get-your-usernameblid-and-password) to run these scripts. To find the blid and password, run dorita980's `get-roomba-password-cloud` tool with your iRobot account information:

```bash
npx get-roomba-password-cloud <your iRobot username> <your iRobot password>
```

### Get last command

This gets the last command that was issued to the Roomba. It's useful for finding the correct data with which to call the Roomba from other smart home systems such as Home Assistant.

```bash
./get-last-command <blid> <password> <Roomba IP address>
```

