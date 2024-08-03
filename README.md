# spotify-difference-in-differencing

[Source](https://engineering.atspotify.com/2023/09/how-to-accurately-test-significance-with-difference-in-difference-models/)

## Situation

You are a data scientist trying to determine the impact of money spent on marketing on podcast show listening.

The following approaches don't work:

1. A/B Testing --> We can't control whether marketing from outside sources (e.g. social media) reach the only the treatment group and not the control group. For example, a person assigned to the control group see a Spotify ad promoting the podcast on Facebook by accident.

2. Post-intervention/pre-intervention difference --> Podcast listening can fluctuate due to many outside factors such as the growth of the Spotify platform or podcast, seasonal trends, episode releases.

## Difference in differences
