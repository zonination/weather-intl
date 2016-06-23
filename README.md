# Weather for 24 International Cities

## Basic information

* Data scraped from Weather Underground.
* Plotted using Rstudio/ggplot2.

All data taken from the city's nearest airport.

Total downloaded file size is about 30MB. Play with `international.R`. Remember to set the correct directory using the `setwd()` command at the top of the code. **I have not included the code I used to scrape Wunderground**, mostly because:

* (a) it would probably tick off the website owner if I initiated a Hug of Death,
* (b) the `.csv` files are already present so what's the point, 
* (c) it only works for Linux (scrapes via `wget`), and 
* (d) it's very poorly written garbage that nobody should use anyway.

`weather-indiv.R` is for individual plots, but make sure you read the commented lines.

A few of these plots on the Temperature plot will have "Grey areas" which indicate that the data is out-of-range. So basically too hot or too cold. You can fix this by changing the scale limits, but it makes the other cities a little less beautiful, so I decided against.

If you're wondering how it's possible to have humidity below water's freezing temperature, [you should read this paper \[PDF\]](http://www.rhs.com/papers/RH_WMO.pdf).

## Full Plot Gallery

![Average Daily Temp for International Cities](http://i.imgur.com/kR1gykE.png)

![Temperature and Humidity Profile for International Cities](http://i.imgur.com/kVCsV36.png)

## Individual cities

I picked the 24 cities based on a balancing act of the following criteria:

* Cities with data-rich sources (some of the best historic data happens to be provided by international airports in the US, so I exclusively used those)
* Cities with high populations (helps with the international airport thing too)
* Cities that are evenly spread throughout the geography of the US. Here's a map of the [international cities](http://i.imgur.com/EbgkYy9.png) I used.
* Cool (and, well, hot) anomalies like Alaska, Hawaii, and Siberia.

## Individual Plots (Gallery)

Below are individualized plots for 24 of the cities on this file, plus a few more I peppered in after planning to use them and then deciding otherwise. **If you want to request me to do a city, send me a message and I'll see what I can do when I have the time.** Feel free to repost these to your city's subreddit; just give attribution.

[Beijing](http://imgur.com/a/RPvvm), [Cape Town](http://imgur.com/a/Yl4LA), [Edmonton](http://imgur.com/a/gmcY6), [Hong Kong](http://imgur.com/a/WLOro), [Jakarta](http://imgur.com/a/8yrWs), [Lagos](http://imgur.com/a/XKDj3), [Lima](http://imgur.com/a/QKIGC), [London](http://imgur.com/a/IGy3K), [McMurdo Station](http://imgur.com/a/Q7D3K), [Mecca](http://imgur.com/a/5Wr5m), [Melbourne](http://imgur.com/a/P6nwb), [Mexico City](http://imgur.com/a/p7sGl), [Moscow](http://imgur.com/a/Xlvzp), [Nairobi](http://imgur.com/a/EkALA), [New Delhi](http://imgur.com/a/lAglF), [Novosibirsk](http://imgur.com/a/oFn89), [Punta Arenas](http://imgur.com/a/LX8Mx), [Reykjavic](http://imgur.com/a/NzukZ), [Rome](http://imgur.com/a/gxKul), [Sao Paulo](http://imgur.com/a/srzhz), [Stockholm](http://imgur.com/a/Vm7D0), [Tehran](http://imgur.com/a/ybO7K), [Tokyo](http://imgur.com/a/cXXay), [Yakutsk](http://imgur.com/a/33IZi)

## Alternate Plots

In addition to these plots, I was able to get some alternate plotting done:

* I was going to do an alt-plot that adjusted for wind chill and heat index, but it looked like it might have been painfully time consuming to tabulate. Perhaps another Redditor can use the data to mess with Texas.

## Other Information:

* For US version, [Click here](https://github.com/zonination/weather-us).
* For Reddit thead, [Click here](https://np.reddit.com/r/dataisbeautiful/comments/46kjr6/a_tale_of_48_cities_the_the_daily_temperature_and/)
