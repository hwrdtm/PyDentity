# Getting Started with SSI development on the Hyperledger Stack
## A tutorial series using the aries-basic-controller library with ACA-Py

With docker installed, run the example using ./manage start

This spins up an aries agent and a notebook for both Alice and Bob. Additionally a local von-network is initialised.

To view the tutorials navigate to:
* [Alice notebook](http://localhost:8888) - this contains the majority of the tutorials
* [Bob notebook](http://localhost:8889) - Bob plays the other half of the protocols when needed.

Both notebooks require a token that can be found in the logs. Fetch the logs for the relevant container using these commands:
* docker logs aries-basic-controller_alice-notebook_1
* docker logs aries-basic-controller_bob-notebook_1