# Social Network Analysis Project 9

## Requirements

- Python 3.10+

## Get started

```shell
# Optional
python3 -m virtualenv env
source env/bin/activate

# install deps
pip install -r requirements.txt
```

## File description

- **generate_dataset.ipynb:** Fetch publication data from arXiv
- **get_authors.ipynb:** Scrape author data from publications lists
- **get_orgs.ipynb:** Scrape organization data from author profiles
- **graphs.ipynb:** Generate histograms
- **network.ipynb:** Generate primary topic network
- **organizations.ipynb:** Generate organization network

## Dataset description

- **authors.csv:** Author profile links
- **authors_complete.csv:** Author and organization data
- **publications.csv:** arXiv publication data

## Matrix description

- **org_matrix.xlsx:** Organization adjancency matrix
- **topic_matrix.xlsx:** Primary topic adjancency matrix
