
# Lunar

Lunar is a recreation of the old Instagram API to revive old versions of the app, it functions on a custom server that isn't linked in any way to the official Instagram servers.

This code is a mess and I do apologize about that, I am still not an expert at writing backend code :/

If you need help setting this up or making it work with your phone, add me on Discord (ppvris) or DM me on [Telegram](https://t.me/xpvris)
 
## Compatibility

**Android:** from 7.17.0 to 10.3.2

**Windows Phone:** 6tag: kinda works?, Instagram Beta: crashes very often

**iOS:** Untested
## Install

*Make sure to have MongoDB on your computer/server first then follow these steps:*

Clone the project

```bash
  git clone https://github.com/dialedup/lunar.git
```

Go to the project directory

```bash
  cd lunar
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`NODE_ENV` (can be production/prod or dev)

`MONGO_URL`

`MONGO_USER`

`MONGO_PASS`


## Configuration

`host` is used to make sure we get the right host link everywhere in the code where it needs it

`autoFollowList` is an arraay of user ID's that will be automatically followed everytime someone makes a new account

`reservedUsernames` are usernames that can't be taken when registering an account, even if an account with that username doesn't exist

## Author & Contributors

**Author:**

- [@lvuu](https://www.github.com/lvuu)

**Contributors:**

- None yet, contributions are always welcome!

## Credits

- Some of the code was taken and rewritten in Node from [@Savefade](https://www.github.com/Savefade)'s [LegacyIGN](https://github.com/Savefade/LegacyIGN) PHP code.
