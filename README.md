# when-are-the-lakes-at-their-bluest

Small project to understand at what month you should go to Banff and Jasper National Parks if you want to see the most blue color of lakes there.
Context - I was planning a trip there, and first I needed to understand when. Different articles advise going there in June, July, or August. But what month has the creaziest blue lakes?
In order to understand this:
we will use Sentinel Hub python package to create a mosaic of selected lakes for each month in a timeframe of 7 years (with Sentinel 2 satellite)
Then we will develop a metric of how blue the lake is or more precisely its pixels (spectrophotometry and colorimetry)
next step is to take pixels of that lake (maybe the whole polygon or maybe just the ones in the centre) and apply this metric to them
finally we can create some beautiful vizualizations like the one I created for Patagonia recently (https://drive.google.com/file/d/1Ba2JebXhiyNJQnqtTvsa1tW1fpArJbT7/view?usp=sharing)

This project is in progress and soon I will upload the Jupyter Notebook for it.
