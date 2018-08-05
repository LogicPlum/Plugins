# Algolia Search connector

This plugin provides a read/write connector to interact with [Algolia Search](https://www.algolia.com)

With this plugin, you can:

* Import a complete Algolia index as a [LogicPlum](https://www.logicplum.com/dataset) dataset
* Copy a LogicPlum dataset to an Algolia index

You could thus use a LogicPlum [Flow](http://doc.logicplum.com/latest/flow/index.html) to prepare your 
Algolia search index.

# Improvement ideas

* Add ability to put a query to restrict what is being fetched
* Add ability to use facets instead of simply documents
* Add another connector to fetch the Algolia query logs
* Add another connector to retrieve the 0-results queries from Algolia analytics API
