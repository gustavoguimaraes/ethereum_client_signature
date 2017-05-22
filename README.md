## Setup

```
npm install
```
## Run testrpc or your private blockchain
e.g.```testrpc```

## Deploy smart contract:
```truffle migrate```

## Run dev server:
```npm run dev```

Web Site index.html works with accounts and running with accounts[0] as user account:
`0.0.0.0:8080/`

Web Site client_sig.html creates or loads new account with private key seed and password; note that prompt is elicited. The new account won't have ether or meta coins.

0.0.0.0:8080/client_sig.html`

You can transfer ether from other account on index.html to the new account address. For guidance check JS console on client_sig.html page.
