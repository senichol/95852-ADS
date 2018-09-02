# 95852-ADS

Possible cryptocurrency data sources via API:

BlockCypher Python-based API (access to Bitcoin, Litecoin, Dogecoin, and Dash with a separate, cURL-based API for Ethereum)
Introduction:
https://www.blockcypher.com/dev/bitcoin/?python#introduction
Transaction (TX) Definitions:
https://www.blockcypher.com/dev/bitcoin/?python#tx
GitHub:
https://github.com/blockcypher/blockcypher-python
This can pull together transaction or block details (e.g. get_transaction_details, get_broadcast_transactions, get_block_details).

GraphSense Web Sockeet and REST APIs (Bitcoin transactions and multiple cryptocurrency exchanges are accessed through a client and stored in Cassandra for retrieval)
Introduction:
http://graphsense.info/
GitHub (Bitcoin client):
https://github.com/graphsense/btc-client
GitHub (Datafeed):
https://github.com/graphsense/graphsense-datafeed
GitHUB (REST API for accessing the Cassandra keyspace):
https://github.com/graphsense/graphsense-REST
