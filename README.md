# Studying the effect of Airbnb in Barcelona
### Table of Contents

1. [Project Motivation](https://github.com/alvaroof/analysis-airbnb-bcn#Project Motivation)

2. [File Descriptions](https://github.com/alvaroof/analysis-airbnb-bcn#files)

3. [Results](https://github.com/alvaroof/analysis-airbnb-bcn#results)

4. [Licensing, Authors, and Acknowledgements](https://github.com/alvaroof/analysis-airbnb-bcn#licensing)

   

## Project Motivation

After hearing about the existence of [Inside Airbnb](http://insideairbnb.com/get-the-data.html); a website that despite the name, share little in common with the [San Francisco's internet company Airbnb](https://es.wikipedia.org/wiki/Airbnb), I felt like obliged to go through the data and, at the very least, see what useful information I could gather from it. If not because I was sure that it was interesting, at least for honoring the surely unbelievable long hours that [Murray Cox](https://twitter.com/murrayscox?lang=es) and his colleagues have spent on this data-gathering and social activism project. 

I focused in Barcelona, first because it is the city I live in, and second, because I, like many others, have also suffered the increasingly unaffordable housing market in the city.

This will likely be a project I'll keep working on and to which I'll be adding more questions and analysis down the road, but for the time being the following questions have been researched:

1. What percentage of listings might actually be run as businesses?
2. Which are the neighborhoods that concentrate the greater number of multiple listings with the same host? 
3. Has the trend in available listings affected the number of rental contracts signed in Barcelona over the years? 

And finally, although not a question, maybe the most important point here:

 4. How can yo replicate a similar analysis for your city?

    

## File Descriptions 

The `main_airbnb_bcn.ipynb` under [/notebooks](https://github.com/alvaroof/analysis-airbnb-bcn/edit/master/data) includes all the analysis, top to bottom. There might be other notebooks consequence of different tests run by me, but they are stored under /test. Feel free to take a look if you're interested. I started to research different functionalities for geojson files, and probably I'll be creating a visualization at some point.

Finally all the necessary data, although it is open and easily downloadable from the web, has been included under /data. It basically comes from two different sources:

- [Open Data BCN](https://opendata-ajuntament.barcelona.cat/data/es/dataset?q=lloguer) - Average price and number of rental contracts in Barcelona for different years and neighborhoods. Quarterly data since 2014.

- [Inside Airbnb](http://insideairbnb.com/get-the-data.html) - Airbnb related data in Barcelona. Quarterly (approx.) snapshots since 2015.

  

## Results

The main findings of the code can be found at the post available [here](https://medium.com/@ortiz.fernandez.alvaro/this-data-about-airbnb-will-make-you-rethink-what-it-is-doing-to-your-city-1318576ba5c4).



## Licensing, Authors, Acknowledgements

I really must give credit to **Murray Cox and the Inside Airbnb team** for their huge effort in not only bringing together all the data from different snapshots of Airbnb webpages but, well, also have initially come up with the idea that something stank in the Airbnb business and that it should be monitored and studied.  

Also thanks to the **Open Data Barcelona Portal**, which is a cool initiative as it allows citizens like to further study what is happening in their cities during this era of technological disruption.

Last but not least, also thanks to the udacity nanodegree in Data Science and the excellent material and guidance they offer there, as this idea started as the first deliverable in that course.

In terms of licensing, you can visit both sources for the data listed in **File Descriptions** to check what are theirs.

The author is only me. Professionally I work as a Data Scientist in the healthcare industry, but have little presence on internet. You can reach me at *ortiz.fernandez.alvaro@gmail.com* should you have any comment, question, or idea to enhance this study in Barcelona.
