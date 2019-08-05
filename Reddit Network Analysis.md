<div align="center">
	<img width="500px" height="170px" src="./Images/reddit-logo.png" />
	<h1>Network Analysis</h1>
	<h3> A "Social Graphs and Interactions" project</h3>
</div>

# Introduction
Reddit is a large famous forum. Most of the users comes from around the world, but the main part comes from the USA. Since reddit is a forum, it is divided into subforums named subreddits. Each subreddit has a name, that reflects the theme of the content to be posted, for example /r/pokemon, is a subreddit for users that want to discuss pokemons, their names, funny stuff about how they look or maybe even ideas of how the new pokemon game is gonna be like. On each subreddit users may post various content, and users of the subreddit can write comments to the posts. If a post is popular, and reaching a certain amount of comments/upvotes per hour, the post will feature on the hot page.

The interesting part about reddit is, that it is a large forum with many different types of people, from rich to poor, tall to small and many other factors. All these people are put together on a global scale and is able to communicate about anything they desire. The behaviour of people on the forum can be interesting to see, and the contents of what people discuss, can be reflected on society.

Each of the major categories is from a subreddit called "TheoryOfReddit". Here people discuss data about reddit, and the categories are originating from a dicussion of a topic on reddit. <a href="https://www.reddit.com/r/TheoryOfReddit/comments/1f7hqc/the_200_most_active_subreddits_categorized_by/">The discussion can be seen be seen here</a>

# The comments

Let's start by looking at the comments and more particularly what they consist of. Below you can see the most used words in each category.

<div align="center">
	<img src="./Images/Clouds.png" />
</div>

* React to clouds

* What is sentiment in texts
* Something about why it is interesting to do in this analysis

<div align="center">
	<img src="./Images/Sentiment_Scores.png" />
</div>

* React to highest and lowest scoring category

* Segway to why it is interesting to do lexical dispersion of those two category
* What is lexical dispersion

<div align="center">
	<h3>News and Issues</h3>
	<img src="./Images/News_Lexical.png" />
</div>

<div align="center">
	<h3>Lifestyle and Help</h3>
	<img src="./Images/Lifestyle_Lexical.png" />
</div>

* React on the two plots

* Segway to network analysis on the subreddits and categories.

# Subreddits and Categories Network

* Networks: why are they interesting
* Subreddit network: Used Louvain to detect clusters of similar reddits, ForceAtlas to draw them in clustered
* Node size is based on how many users two nodes have in common with its neighbors
* Note that the biggest nodes are clustered together in the midelle

<div align="center">
	<img src="./Images/Subreddit_Network.png" />
</div>

* Did the exact same thing as above, but with the categories
* Unsurprisingly they are still clustered after size.

<div align="center">
	<img src="./Images/Categories_Network.png" />
</div>

* Erased all edges but the strongest one to show which category the other categories share the most users with. All link to 'Images, Gifs and Videos'
* Most likely because 'Images, Gifs and Videos' has the most subreddits.
* Reference bar graph below, which shows the number of reddits in each category.

<div align="center">
	<img src="./Images/Categories_Network_strongest.png" />
</div>

<div align="center">
	<img src="./Images/Categories_subreddit_count.png" />
</div>

* Finally; a confusion matrix which shows the percentage of shared users between each category
* Notice that 'Sports'/'Race, Gender and Identity' is lowest
* 'Humor'/'Images, Gifs and Videos' is the highest.

<div align="center">
	<img src="./Images/Users_Overlap_Matrix.png" />
</div>