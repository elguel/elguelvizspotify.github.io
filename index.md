## Welcome to Spotify viz

<img src="assets/css/logo@2x.png" alt="hi" width="50%" height="50%" class="inline"/>



This visualization page is created to explore **Spotify** listening habits of people in 4 Nordic countries - Finland, Sweden, Norway and Denmark - over a period of January - March 2020.

Let's see what they look like!

### Daily TOP-200 songs data 

The data was collected from daily TOP-200 chart using the defined time frame.
Let's see average streaming over 3 months of 2020 and compare it to the previous year - we see that average number of streams was larger than in 2019, although the number dropped in March to a level below the 2019 level.

{% include yoy.html %}

To understand listening habits of the 4 Nordic countries better, it's good to check distribution of **song characteristics**. Measures of song characteristics is something that Spotify provides.
The following song characteristics were included:
- tempo (tempo of a track in beats per minute (BPM))
- danceability (a value of 0.0 means least danceable and 1.0 means most danceable)
- acousticness (a confidence measure from 0.0 to 1.0 of whether the track is acoustic)
- loudness (psychological correlate of physical strength (amplitude, in db))
- duration (track duration in ms, converted to minutes for the visualization)
- popularity (measure based on the total number of plays compared to other tracks and how recent those plays were)
- energy (a value of 0.0 means least energetic and 1.0 means most energetic)

For more details, see [Spotify audio features](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/).

{% include groupedchars.html %}

This chart below provides more insight on how average song characteristics differ between the 4 countries. We can see that they are quite similar.

{% include 2020chars.html %}

And this is a chart for **2019 data**. We see that there is not much difference between the 2 years.

{% include 2019chars.html %}

Let's check also the **average number of streams per 1000 people**, plotted on the map. Finland seems to have the smallest number.

{% include countries20.html %}

### What about COVID-19?

Another thing that was on my mind was checking the overall COVID-19 cases development against the development of listening patterns. It does not seems to have much effect.
{% include COVID.html %}


### Thank you!

This was it, hope you enjoyed my visualization! 
