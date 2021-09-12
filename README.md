# defi_tutorial

## Dependencies

- Nodejs v14.17.4
- [Ganache](https://www.trufflesuite.com/ganache)
- truffle@5.1.39
- [Metamask Google Chrome](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)

## Build

Install Dependencies
```
$ npm install
```

Test
```
$ truffle test
```

Compile
```
$ truffle compile
```

Deploy
```
$ truffle migrate
```

Start Frontend
```
$ npm run start
```

Mint the earned tokens to the stakers
```
$ truffle exec scripts/issue-token.js
```
