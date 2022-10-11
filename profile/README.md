
# clu3 🤖

Use clu3 to get rid of the undesired bots putting hands on your smart contracts! 🤖

## Appendix

clu3 is an easy to implement modular service that works with an easy to integrate modular Solidity function that lets any Smart Contract to add any humanity proof (modular) between functions to avoid the bots automatic transactions, in example a CAPTCHA (as seen in our demo site).

Everyone in the space hates undesired bots transacting within us! the developers when they are willing to open a project to the real community for their organic growth and the degens when are going for their slot in some activation but is late because the bots got everything in 0.69 milliseconds.

To do so we use a Keccak-256 signed string made by: a timestamp, one senderAddress and one unique id (clu3_id) to reference each implementation, so we can avoid: 
1º Signature mining by getting many transactions ready to use together (aka farming).
2º Transaction hijacking, by capturing the signature in the pending transaction of other and use it paying more gas.
3º Signature re-use, by sending the same data in a new transaction to a different function or smart contract that uses the same validator/signer.

In the SC we set the filters to confirm a valid transaction, letting pre-configured whitelisted addresses to bypass the filter (for the own developers/functionallity purposes) and a modular read/write web3 storage service buffer connection to check used timestamps, for our prototype demo site we use onchain storage.

## Features

- Modular HumanityProof service.
- Modular web3 storage service.
- WhiteList support.

## Tech Stack

**Client:** React.

**Backend:** Node, Solidity.

    
## Demo

[clu3.framer.website](https://clu3.framer.website/)

## Documentation

[clu3-1.gitbook.io/clu3](https://clu3-1.gitbook.io/clu3/)

## Twitter

[https://twitter.com/clu3service](https://twitter.com/clu3service)

## Authors

- [@giangp_](https://twitter.com/giangp_)
- [@ariutokintumi](https://twitter.com/ariutokintumi)


## FAQ

#### Will this save the space?

Yes, of course!

#### Do I have to pay to use it?

Never on our implementations or using this source code.

#### Are you going to offer a free to use service?

Depending on the Grants and Foundings we can get, there is expenses to build an open service.

## Usage/Examples

- Mint Sites
- Dataforms protected SC (data should be submited prior interaction)
- Agenda
- Queues
- Claims
- Whatever needs to get b0ts away!

## License

[MIT](https://choosealicense.com/licenses/mit/)

