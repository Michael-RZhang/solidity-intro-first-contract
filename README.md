# Intro to Solidity & Writing/Deploying your First Contract

For Oakland Blockchain Developers: A class going over the basics of the solidity language &amp; developing/ deploying your first contract.

Web3 1.0 is only in beta and I had some trouble calling my function from a deployed contract. You can follow the instructions in `walkthrough-web3-1.0beta.md`. If you want to walk through on a non-beta version, follow the instructions in `walkthrough-web3.0.19.0.md`

Shout out to [Decypher](decypher.tv), got the 0.19 version instructions from him. His videos are awesome, I'd strongly recommend checking him out!


- [Web3 1.0 BETA Documentation](https://web3js.readthedocs.io/en/1.0/index.html)
- [Web3 0.17.0 alpha Documentation](https://github.com/ethereum/wiki/wiki/JavaScript-API)



#### Adding clear to node console
I like adding this to my node console when I'm working. Then you can call the `clear` function and it will move all text to top of screen.
```js
function clear() {
  process.stdout.write('\u001B[2J\u001B[0;0f');
}
```

---
[Rachel Ralston](http://www.rachelralston.com)  |  [twitter](http://www.twitter.com/rachelralston)  |  [medium](http://www.medium.com/@rachelralston)  |  [linkedIn](http://www.linkedin.com/in/rachelralston)

[Oakland Blockchain Developers](http://www.blockchaindevelopers.io)
