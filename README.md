# Analyzing article histories and authors interaction on Wikipedia using Apache Spark 

1. Download Wikipedia-Dump file **enwiki-*.xml.bz2** (https://dumps.wikimedia.org/enwiki/)
2. Convert downloaded archived XML to JSON by executing **xmlparse.py** script
3. After that it could be used for executing scripts from ./spark/* to get data about articles with the most comments, the most edits by month, edits by authors and etc.

