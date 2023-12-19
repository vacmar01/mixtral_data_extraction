# Mixtral-8x7B-Instruct-v0.1 Information Extraction

This repo includes a notebook which shows how to use Mixtral to extract people's names from a text file and return the names as json. 

It validates the response to be valid json using `pydantic`. 

In my experiments so far Mixtral returns valid json in 100 % of the cases. Sometimes it also returns some prose together with the json, but this is easily filtered by something like `.split('\n\n')`. 

By the way, the text used is from this video: [https://www.youtube.com/watch?v=o84GXnrHdgg](https://www.youtube.com/watch?v=o84GXnrHdgg).