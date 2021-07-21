# George

## Simple NPC game interactions using a stateful contract and atomic transfers
![intro](intro.png)

DISCLAIMER: NO WARRANTY INCLUDED: This contract is for tutorial purposes and 
hasn't been through a security audit. Use this contract on mainnet AT YOUR OWN RISK!
I won't be responsible for any loss incurred.

```
# node
make pvtnet     # create private net
make start      # start private net
make stop       # stop private net

# ci
make build      # build contract
make deploy     # deploy contract

# interact
make read       # read global state
make heal       # heal npc
make injure     # damage npc
make kill-npc   # run `injure` 6 times
make transcend-npc # run `heal` 6 times
make delete     # retire the app
```

If you've enjoyed this article you can tip me at:
`MFXIM527GPYS3N5RFRTDL7Y2LCGHFYNODSE7SCQB6ZMQ5KGDDTW3K26W4E`
