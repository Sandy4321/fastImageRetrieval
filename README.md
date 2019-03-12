# fastImageRetrieval
fastImageRetrieval BenchMarking

I tried to make the vector embedding comparisons and sorting faster using numpy broadcast, parallel euclidean distance calculation, numba compiled quick sorting algo. I have tested it for very large comparisons till 2 lakhs image embeddings as well for a query image.
For 10k comparisons , results come back in 0.3 sec on my local machine (less than 1 core used).
for 200k results come back in 1 sec on my local machine (less than 1 core used).
