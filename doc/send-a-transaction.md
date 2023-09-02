# Send a Transaction

## `sendtoaddress`:

```
./src/redblockd -fallbackfee=0.0001
ADDR=$(./src/bsha-cli getnewaddress)
TXID=$(./src/redblock-cli sendtoaddress $ADDR 49.999)
```

## `createrawtransaction`:

Use input(s), by txid and vout, to create spendable outputs at destination addr(s). Leftovers become fees collected by miners; be sure to account for change from your inputs. This example input spents most of a 50 REDB coinbase reward.

```
./src/redblockd
RAWTX=./src/redblock-cli createrawtransaction "[{\"txid\":\"txid\",\"vout\":0}]" "{\"axxxxxxxxxxxx\":49.999}" 
SIGNEDRAWTX=./src/redblock-cli signrawtransactionwithwallet $RAWTX
BROADCASTEDTXID=./src/redblock-cli sendrawtransactionwithwallet $SIGNEDRAWTX
```
