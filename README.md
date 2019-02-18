# cryptocurrencies-and-wikipedia

This repository provide the data and relevant code for the paper ["Wikipedia and Digital Currencies:
Interplay Between Collective Attention and Market Performance"]( https://arxiv.org/abs/1902.04517)

## Data provided
	- wiki_market.csv: Market data and Wikipedia data (total daily views and edits) for 38 cryptocurrencies.
	- all_edits.csv: all edits for the 38 cryptocurrencies, including reverts and vandalism.
	- reverts.csv: reverts only edits.
	- vand.csv: only edits.
	- top_editors_outside.csv: top pages and number of edits top editors contribute when consider the entire Wikipedia.
	- returns_random.csv: returns from random strategy.
	- returns_price.csv: returns from price strategy.
	- returns_wiki.csv: returns from wikipedia strategy.
	- start_ends.csv: returns considering different starts and ends for the three strategy.
	- net_res.csv: all results from the network analysis.
	- centrality.csv: centrality measure for the network.
	
## Notebooks 
	- Paper: replication code for the figures and values in text.
	- Strategy implementation: price, wikipedia views and random strategy implementation.  
