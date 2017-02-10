# TranscendentiPy

## Description

TranscendentiPy is a markov chain based text generator that was fed a healthy diet of Transcendentalist poems from poemhunter.com's collection of Walt Whitman, Henry David Thoreau, and Ralph Waldo Emerson poems.

## How to Use

Website to come!

## Contents

- `transcendentiPy.ipynb` : iPython notebook that scrapes our poem data and creates our poems

- `corpus.txt` : the text file containing all of our poem data from the initial scrape

## Improvements

- Set up heroku so we can see new poems on a browser refresh
- Better data storage strategy: have each authors individual poems in a txt file, in a directory titled after the author. Write a script to join all of these contents into the corpus rather than scraping directly to corpus.
- Add user weightings so the output can be 80% henry-david-thoreau, 10% Whitman, etc
- Add poet query capability to scrape the collection of poem's for an author of the user's choosing
