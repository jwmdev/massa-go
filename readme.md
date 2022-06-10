# Massa API GO library

An unofficial Golang library for [#Massa](https://massa.net ) blockchain.

![massa-go](https://raw.githubusercontent.com/jwmdev/massa-go/master/media/massa-go.svg)

### Requirements

- GO go 1.17+

### Installation

```bash
go get -u github.com/jwmdev/massa-go
```

### Links
- [Massa: Massa main website](https://massa.net)
- [Testnet: Massa testnet](https://test.massa.net)
- [Testnet: Massa testnet](https://massa.net/testnet)
- [Massa Github: Massa official github repository](https://github.com/massalabs)
- [Massa API: Massa official api documentation](https://github.com/massalabs/massa/wiki/api)

## Methods
### Public API (node_ip:33035)
- [ ] get_status
- [ ] get_cliques
- [ ] get_stakers
- [ ] get_operations
- [ ] get_endorsements
- [ ] get_block
- [ ] get_graph_interval
- [ ] get_addresses
- [ ] send_transaction
- [ ] buy_roll
- [ ] sell_roll
- [ ] ExecuteSC (execute smart contract)
- [ ] get_filtered_sc_output_event
### Private API (node_ip:33034)
- [ ] stop_node
- [ ] node_sign_message
- [ ] add_staking_private_keys
- [ ] remove_staking_addresses
- [ ] get_staking_addresses
- [ ] ban
- [ ] unban

## License

This package is released under the MIT license.
