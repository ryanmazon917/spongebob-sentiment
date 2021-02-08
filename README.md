# Sentiment Analysis of Squidward Tentacles :squid:

## Summary
Growing up I used to love watching SpongeBob on TV. The contrast between the different characters in the Bikini Bottom makes for an entertaining show. One running theme throughout the show is the characterization of a grumpy Squidward Tentacles. Squidward enjoys peace, quiet, and the finer things in life, and is clearly bothered by Spongebob's constant noise-making and fooling around. But just how grumpy is Mr. Squidward? And how does his negativity evolve throughout the duration of the show? I had a theory that Squidward actually 'cheers up' as time goes on, and I think this may be attributed to a change in corporate strategy. It would make sense if it were the case that the creators of Spongebob cleaned up Squidward's act to make the episodes more appealing as a children's show. Using data science, I put this theory to the test and came up with some interesting results!

## The Process (Summarized)
![data processing flowchart](images/spongebob-sentiment-diagram.png)

## Technologies Used
- Python: pandas, numpy, matplotlib/seaborn
- Web scraping, data processing, machine learning, data visualization
- Google Cloud Natural Language API

## The Results
I compiled a list of everything Squidward said in each episode of the TV series. I ran the data through a sentiment analysis model and computed an average score for each episode. There are about 300 total episodes, and because they are chronological, we are looking at a time series plot. Also included in the figure are the 10-day and 20-day simple moving averages.
![squidward sentiment time series graph](images/squidward_chart_edited.jpg)

## What I Learned


## Future Implementations
