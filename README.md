# Enviroment Setup

## Operating System Requirement

* Ubuntu 16.04+ or CentOS 7

## Setup Second State Devchain

Please refer to our online documentation [1] for more detials.

[1]: https://docs.secondstate.io/devchain/getting-started

Please remember your URLs, which represent your blockchain’s RPC node and ElasticSearch service. We will use them at the next step to setup our BUIDL IDE.

## Setup BUIDL, Second State Online IDE

After you finished the Devchain setup, please use the following steps to connect your devchain with our BUIDL IDE.

1. Access the BUIDL IDE from your browser: https://buidl.secondstate.io/
2. Connect your own devchain to our BUIDL
	1. Click `Providers` icon to active BUIDL config panel.
	2. Set the `Set ES Provider Endpoint` to `Customize`.
		1. Put your URL of ES Provider Endpoint here.
	3. Set the `Set Web3 Provider Endpoint` to `Customize`.
		1. Put your URL of Web3 Provider Endpoint here.
		2. Set your Chain ID here, please make sure the Chain ID is the same as devchain.
	4. If you want to set the Transaction Gas Limit or Gas Price, click the checkbox `Custom Tx Gas`.
3. Once you are done, your BUIDL contracts and DApps will now deploy to the new blockchain!

## Upload and Execute RRBIC smart contract

### Smart Contracts

### How to use it
