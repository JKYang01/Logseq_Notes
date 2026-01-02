class:: template
alias:: Journal Template
tags:: 
book:: 
iteration:: [[May 23rd, 2024]] [[Jul 22nd, 2024]] [[Sep 16th, 2024]] [[Jul 17th, 2025]]

- ## how
	- today journal 
	  template:: today journal 
	  template-including-parent:: false
		- TODO Today I read
			-
		- **TODO** Today I pracetices
			- {{query (and (task todo) (between -3d -1d))}}
			- **daily routine**
				- TODO Practive DSA at least 5；
					- {{query (page-property :created <%today%> )}}
				- TODO Iterate old notes of this week；
					- {{query (page-property :iteration <%today%> )}}
		- Today I **LEARNED**
			- TODO [[Machine learning]] | [[Math]]
- ## inbox
	- TODO deep research
		- {{query (and (page-property :class "deep_research") (page-property :created <%today%> ))}}
	- TODO post on medium；
- ## ref.
- ## related
- ## archive