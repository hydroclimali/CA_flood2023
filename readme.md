This repository holds a few scrappy notebooks that I developed in a couple days to perform some simple analyses of the 2023 California floods.
I have shared the visualization result on Linkedin: https://www.linkedin.com/posts/ahmadalipour_california-was-impacted-by-a-series-of-atmospheric-activity-7022087426865041409-3VQH

One thing to note is that I had some trouble installing cfgrib on my Macbook M1 laptop. Since I didn't want to spend too much time debugging that, I decided to use Google Colab to convert .grib files to .nc, select the area of interest, and download the converted nc files and use them for the analyses.
Normally (if cfgrib installation works well), the analysis will be much easier and one can simply use xarray to analyze grib files. Here's an example for that:
https://docs.xarray.dev/en/stable/examples/ERA5-GRIB-example.html
