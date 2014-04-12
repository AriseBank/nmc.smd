# Namecoin JSON-RPC Spec
This is a JSON specification for Namecoin JSON-RPC API which conforms to the [Service Mapping Description](https://en.wikipedia.org/wiki/Service_Mapping_Description) (SMD) format.  It is incomplete, and contributions are strongly encouraged.

##Complete
* name_show
* name_filter
* name_scan
* getinfo
* getblockcount

##Not included
### Namecoin Specific
* name_clean
* name_debug
* name_debug1
* name_firstupdate
* name_history
* name_list
* name_new
* name_update

###Bitcoin
* addmultisigaddress
* addnode
* backupwallet
* createmultisig
* createrawtransaction
* decoderawtransaction
* dumpprivkey
* encryptwallet
* getaccount
* getaccountaddress
* getaddednodeinfo
* getaddressesbyaccount
* getbalance
* getbestblockhash
* getblock
* getblockhash
* getblocktemplate
* getconnectioncount
* getdifficulty
* getgenerate
* gethashespersec
* getmemorypool
* getmininginfo
* getnewaddress
* getpeerinfo
* getrawchangeaddress
* getrawmempool
* getrawtransaction
* getreceivedbyaccount
* getreceivedbyaddress
* gettransaction
* gettxout
* gettxoutsetinfo
* getwork
* importprivkey
* keypoolrefill
* listaccounts
* listaddressgroupings
* listreceivedbyaccount
* listreceivedbyaddress
* listsinceblock
* listtransactions
* listunspent
* listlockunspent
* lockunspent
* move
* sendfrom
* sendmany
* sendrawtransaction
* sendtoaddress
* setaccount
* setgenerate
* settxfee
* signmessage
* signrawtransaction
* stop
* submitblock
* validateaddress
* verifymessage
* walletlock
* walletpassphrase
* walletpassphrasechange