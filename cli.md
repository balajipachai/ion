
# ION CLI

### Installation

1. Clone the ION repository: `git checkout master`
2. Install the project globally: `git install -g`
3. Use one of the supported commands below (currently limited to Create).

### Commands

#### Create Operation
```
ion operation create
```
To publish your DID operation, you will need to anchor the generated create operation payload in the Bitcoin blockchain using your own ION node, or another you can send the operation to. If you anchor your DID operation via your own node, you should leave your ION node running locally (which includes an IPFS node internally) to ensure your operation is propagated to the rest of the peer in the ION network.