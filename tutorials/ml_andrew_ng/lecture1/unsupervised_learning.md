# Unsupervised Learning

Here is a data set. Can you find some structure in the data?	

Examples:
- Clusterization of articles
- DNA genes clusterization
- Organize computer clusters (???)
	- Which machines tend to work together and if you can put those machines together, you can make your data center work more efficiently
- Social network analysis
- Market segmentation
- Astronomical data analysis (how galaxies are formed)
- Cocktail party problem (!!!)
	- 2 mics
	- each microphone records a different overlapping combination of these two speaker voices
	- separate out these two audio sources that were being added or being summed together
	- [W, s, v] = svd((repmat(sum(x.\*x,1, size(x, 1),1).\*x)\*x')
	