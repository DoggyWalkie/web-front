### TL;DR

* https://doggywalkie.netlify.com/index.html - dog owner page
* https://doggywalkie.netlify.com/walker.html - dog walker page

### Documentation

This is an tutorial/exemplary Ethereum application for dog owners
to contact other dog owners who can walk their dogs. Application
consists of three parts:

 * front-end
   * dog owner screen -- webapp that talks with offchain backend
     * select walk date and time
     * save data to necessary to find a walker
   * dog walker screen -- webapp to accept walk proposal
     * create token through web3 interface
 * [backend](https://github.com/DoggyWalkie/web-server)
   * realtime list of nearby walkers for walk request
 * [smart contract](https://github.com/DoggyWalkie/eth-contract/blob/master/build/contracts/DoggyWalkie.json)
   * derived from standard token
   * extended to include date and time of the walk
