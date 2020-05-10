## Welcome to Spotify viz

![useful image](elguelvizspotify.github.io/assets/spotify-logo.png)

You can use the [editor on GitHub](https://github.com/elguel/elguelvizspotify.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

This visualization page is created to explore Spotify listening habits of people in 4 Nordic countries - Finland, Sweden, Norway and Denmark - over a period of January - March 2020.

Let's see what they look like!

### Daily TOP 200 songs data 

Let's see how average streaming developed over 3 months of 2020 and compare it to the previous year - we see that average number of streams was larger than in 2019, although the number dropped in March to a level below the 2019 level.

{% include yoy.html %}

To understand the listening habits of the 4 Nordic countries better, it's good to check distribution of song characteristics. Measures of song characteristics is something that Spotify provides.
The following song characteristics were included:
- tempo
- danceability
- acousticness
- loudness
- duration
- popularity
- energy

{% include groupedchars.html %}

This chart provides more insight on how average song characteristics differ between the 4 countries:

{% include 2020chars.html %}

And this is a chart for 2019 data. We see that there is not much difference between the 2 years.

{% include 2019chars.html %}

Let's check also the average number of streams per 1000 people, plotted on the map. Finland seems to have the smallest number.

{% include countries20.html %}

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### What about COVID-19?

Another thing that was on my mind was checking the overall COVID-19 cases development against the development of listening patterns. It does not seems to have much effect.
{% include COVID.html %}


### Thank you!

This was it, hope you enjoyed my visualization! 
