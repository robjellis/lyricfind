# LyricFind Corpus

(Cross posted from [here](https://www.smcnus.org/lyrics/).)
Welcome to the LyricFind Corpus, developed at the [Sound and Music Computing Laboratory](https://www.smcnus.org/) at the National University of Singapore, with the very gracious support and partnership of [LyricFind](http://www.lyricfind.com/), a world leader in legal lyrics licensing and retrieval.

In addition to providing the raw data which comprises the analyses in our [ISMIR 2015 paper](http://robjellis.net/papers/Ellis_Xing_Fang_Wang_ISMIR_2015.pdf) “Quantifying Lexical Novelty in Song Lyrics”, we are also pleased to provide 275,905 distinct lyrics in bag-of-words format (67.6 million total word instances), along with identifying lyric, artist, and album IDs that can be cross-referenced with the LyricFind ecosystem.

We believe that this dataset marks the largest and cleanest set of lyrics in bag-of-words format yet available, although comparisons with the Million Song Dataset’s [musiXmatch lyrics corpus](https://labrosa.ee.columbia.edu/millionsong/musixmatch) are certainly warranted!

The following six files are packaged a single large .zip file, available for download in either in .txt format or .xlsx format:
### [Download in .txt format](http://www.smcnus.org/data/lyricfind_corpus_txt.zip)
### [Download in .xls format](http://www.smcnus.org/data/lyricfind_corpus_xlsx.zip)
- A set of cleaning rules (and a Python script), used to standardize the orthography of the original lyrics.
- A 66,975-item list of valid dictionary words used across the lyrics corpus, along with their document and corpus frequencies from the lyrics corpus. For convenience, the document and corpus frequencies associated with the [SUBLTEX-US corpus](https://www.ugent.be/pp/experimentele-psychologie/en/research/documents/subtlexus) are also provided (please do note the appropriate citation for this data). The “wordID” index is used to identify words in the bag-of-words format.
- A large file containing the set of wordIDs (including repeated words) for 275,905 lyrics.
- A cross-reference file which associates the 275,905 distinct lyrics with a larger set of 360,919 lyrics that includes “duplicates” of the 275,905 distinct lyrics across different recordings/artists.
- A metadata file comprising song title, artist name, and album title for 360,919 lyrics. Our recently developed Lexical Novelty Score is also provided for each lyric.
- LyricFind IDs associated with two lists from Billboard Magazine: the [All-Time Top 100 Songs](https://www.billboard.com/articles/list/2155531/the-hot-100-all-time-top-songs) and [All-Time Top 100 Artists](https://www.billboard.com/articles/columns/chart-beat/5557800/hot-100-55th-anniversary-by-the-numbers-top-100-artists-most-no).

For information about any of the content described here, please contact [Associate Professor Ye Wang](mailto:wangye@comp.nus.edu.sg) at the SMC Lab.

For further queries about other ways in which LyricFind could be incorporated into your research, please contact [Roy Hennig](mailto:roy@lyricfind.com), LyricFind’s Director of Sales.

### Paper citation:
Ellis, R.J., Xing, Z., Fang, J., & Wang, Y. (2015). Quantifying lexical novelty in song lyrics. Proceedings of the 15th International Conference on Music Information Retrieval.

## Sample finding:
<img src = 'LNS_artist.png'>
