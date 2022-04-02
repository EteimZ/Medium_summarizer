# Medium Summarizer

This is a project to build a summarizer for medium articles.

Give a medium article **M** the pass through a summarizer model **T** the summarizer outputs the summary of the article **S**

M -> T -> S

## Getting and preprocessing the article.

The first step is to scrape the medium post and grab all texts related to the article. Removing things like images or other related posts. This solution has to be general. It should work for any medium article. Scraping will be done with **beautiful soup**

## Summarize the artle
The article will be summarized using Huggingface🤗 **tranformers** library.

## The summary
The output will be displayed in a web page.