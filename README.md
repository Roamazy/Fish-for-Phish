# Fish-for-Phish
Neural network and data processing

A side project (still in process) of training a neural network to flag phishing websites based solely on discreet elements of a URL. 
I started with a data set which was already binary coded as safe or phishing. The issue was that I wasn't able to add to it, as I wasn't able to replicate many of its columns (such as domain age). So, I trained a neural network on the original data and noted the accuracy. 
Then, I stripped away all but the websites and phishing tag, and repopulated the dataframe using an exhaustive function which analyzes elements of the URL itself. I was able to achieve accuracy within a percentage point, and without the need for domain lookups.
