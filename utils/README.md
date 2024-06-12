# Tools

## Get BM25 result

Run `python utils/bm25.py` to generate BM25 results for the instructions and readme. Ensure to update the original dataset `path` and output `path` which includes the BM25 results.

## Crawl README files from github repository

Run `python utils/crawl.py` to fetch readme files from a specific GitHub repository. You'll need to modify the `url` within the code to retrieve the desired readme files.

## Crawl raw repositories
Run `bash utils/crawl_raw_repo.sh` to clone repositories and write repositories to txts.

## Calculate number of tokens
Run `python utils/calculate_num_tokens.py` to calculate the number of tokens statistics in the dataset.