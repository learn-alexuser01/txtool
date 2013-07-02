
Build bitcoin transactions
--------------------------
Usage: txtool [options] COMMAND [command parameters]

Options:
  -f, --file  Load/store transaction state to/from FILE  [required]


txtool command summary
----------------------

help
	List this command summary

init
	Initialize new transaction state database

multisig N-REQUIRED KEY1 KEY2 KEY3...
	Begin new multi-sig tx

nreq N-REQUIRED
	Specific number of sigs required for a multisig tx

pubkeys KEY1 KEY2 KEY3...
	Add to list of pubkeys / bitcoin addresses

pubkeys.clear
	Clear list of pubkeys

raw SERIALIZED-TX
	Input serialized transaction from command line

raw.read FILE
	Input serialized transaction from file

raw.write FILE
	Output serialize transaction to file

raw.clear
	Clear serialized tx data

show
	Inspect internal transaction state
