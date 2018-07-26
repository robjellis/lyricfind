# LyricFind Corpus

Welcome to the LyricFind Corpus, developed at the Sound & Music Computing laboratory at the National University of Singapore with the very gracious support and partnership of LyricFind, a world leader in legal lyrics licensing and retrieval.

In addition to providing the raw data which comprises the analyses in our ISMIR 2015 paper “Quantifying Lexical Novelty in Song Lyrics”, we are also pleased to provide 275,905 distinct lyrics in bag-of-words format (67.6 million total word instances), along with identifying lyric, artist, and album IDs that can be cross-referenced with the LyricFind ecosystem.

We believe that this dataset marks the largest and cleanest set of lyrics in bag-of-words format yet available, although comparisons with the Million Song Dataset’s musiXmatch lyrics corpus are certainly warranted!

The following six files (along with this associated README.pdf) are packaged a single large .zip file, available for download in either .txt. or .xlsx.

- A set of “cleaning” rules (and a Python script), used to standardize the orthography of the original lyrics.
- A 66,975-item list of valid dictionary words used across the lyrics corpus, along with their document and corpus frequencies from the lyrics corpus. For convenience, the document and corpus frequencies associated with the SUBLTEX-US corpus are also provided (please do note the appropriate citation for this data). The “wordID” index is used to identify words in the bag-of-words format.
- A large file containing the set of wordIDs (including repeated words) for 275,905 lyrics.
- A cross-reference file which associates the 275,905 distinct lyrics with a larger set of 360,919 lyrics that includes “duplicates” of the 275,905 distinct lyrics across different recordings/artists.
- A metadata file comprising song title, artist name, and album title for 360,919 lyrics. Our recently developed Lexical Novelty Score is also provided for each lyric.
- LyricFind IDs associated with two lists from Billboard Magazine: the All-Time Top 100 Songs and All-Time Top 100 Artists.
