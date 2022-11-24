## Setup

### Prerequisites
* [Docker](https://docs.docker.com/get-docker/)
* [Go 1.18](https://go.dev/dl/)

### Installation
1. Clone this repository
2. Run `git submodule update --init`

Everytime you need to pull in changes from a client, run `git submodule update --remote`

## Running the Devnet
1. (_Optional_) Run `make devnet-clean` to start from a clean slate
2. Run `make devnet-up`
3. Visit http://127.0.0.1:16686 to visualize beacon and validator node traces
