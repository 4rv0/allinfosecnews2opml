# allinfosecnews2opml
A small python script to convert the RSS feeds listed in https://github.com/foorilla/allinfosecnews_sources and convert them to OPML for easy importing to an RSS reader

## installation and execution
1) clone this repo
2) clone https://github.com/foorilla/allinfosecnews_sources
3) from this repo, set up a python3 venv
```
$ python3 -m venv venv
$ . ./venv/bin/activate
```
4) install requirements
```
$ python3 -m pip install -r ./requirements.txt
```
5) run the script
```
$ python3 ./allinfosecnews2opml </path/to/allinfosecnews_sources/README.md> > <outfile.opml>
```
## or you can just grab the output file I made

It's "allinfosecnews_sources.opml", and was added on August 7th, at 2:00PM PST.


