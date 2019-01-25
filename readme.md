# Elasticsearch presentation

## Presentation Outline
- basic:
	- everything's an array:
		- term
		- match
		- index
	- analysers:
		- tokenisers: the string.split of elasticsearch
		- filters: exclude text or tokens from your indexed data. strip out html,
		remove stop words like "or", "and", "then".
	- queries:
		- match
		- term
		- bool
		- ranking
- debugging:
	- your fren: curl
	- check your mapping
	- check your data
	- your fren: tcpflow / tcpdump
	- check your query
