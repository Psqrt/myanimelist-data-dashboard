# myanimelist-data-dashboard
MyAnimeList.net dataset interactive dashboard on R markdown (flexdashboard package)

This is a dashboard about animes (TV, Movies, and others). You can find out details about anime types, genres, evolution, scores, etc. If the first tab gives a first insight of anime world, the two next ones focus on the two main anime types : TV and Movies. The last tab allows you to examine the different anime studios separately.

Check out the “about” tab to know the data sources, inspirations, acknowledgements and tools used here.

The dashboard is fully interactive, do not hesitate to put your mouse on visualisations and try to click on Anime photos to be redirected to the MyAnimeList’s anime page!

## Inspiration

* This dashboard was made after seeing tavoosi’s incredible interactive dashboard about suicide data (https://www.kaggle.com/tavoosi/suicide-data-full-interactive-dashboard).
* Flexdashboard is a perfect compromise between Rmarkdown reports and Shiny apps. The HTML output can be used without a running R session and loading the dashboard doesn’t take time unlike on kaggle.

## Data Source

* The dataset used here is from azethoth42’s “MyAnimeList Dataset” (https://www.kaggle.com/azathoth42/myanimelist).
* Anime photos are directly loaded from MyAnimeList.net website.
* The main page’s illustration has been taken from : https://www.elsetge.cat/pngvi/hmRxih_wallpaper-simple-background-princess-mononoke-no-background/. I couldn’t find out the original author.
* The about page’s illustration has been taken from : https://detectiveconaninternational.blogspot.com/2017/02/. I couldn’t also find out the original author.

## Tools used

* The code is written and executed on R language (R markdown script).
* The dashboard has been made with the R package : flexdashboard.
* Visualisations have been produced with highcharter and plotly R packages.
