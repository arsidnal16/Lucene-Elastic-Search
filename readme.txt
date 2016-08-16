1. HW4. java is the source code for indexing and retrieval. To plot the graph uncomment the method plotchart(entry.getKey(), entry.getValue()).

2. SortedSid.txt is the sorted (by frequency) list of (term, term_freq pairs)

3. Zipf law curve is the plot of the resulting Zipfian curve

4. top100results contains the Four lists (one per query) each containing at MOST 100 docIDs ranked by score (optional: provide a text snippet of 200 chars along the DocID).

5.comparison.pdf contains the table comparing the total number of documents retrieved per query using Lucene’s scoring function vs. using your search engine (index with BM25) from the previous assignment