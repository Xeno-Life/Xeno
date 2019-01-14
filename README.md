# About

Xeno is a political metasearch engine inspired by Google designed to burst filter bubbles.

# Why

Algorithms control the information we consume in our digital lives. From personalized searches to tailored news feeds to targeted ads, the informational filter bubble which we all inhabit is ever-present and has broad implications. In many cases we consume starkly different information from different sources, making it difficult to converge on our collective reality. The term filter bubble was coined by Internet activist Eli Pariser in 2010 and has only become more and more relevant with time. How can we empower people to understand the nature of the bubbles in which they exist and to navigate information space in a free and unconstrained way? Our answer lies in a combination of metasearch and algorithmic transparency.  

# What

Metasearch is a tool that takes input from a user and sends out multiple queries for different results. Our version of metasearch allows a user to enter a search query to view a spectrum of various filter bubbles. If a user can move freely from a right-wing filter bubble to a left-wing filter bubble (and everything in between) then they can understand the larger picture of the flow of information online, which we hope will lead to a greater sense of empathy and understanding between people of various political dispositions.

Algorithmic transparency is the principle that the variables that influence the decisions made by algorithms should be visible to users.
Companies like Google and Facebook do not implement algorithmic transparency, so users feel as though the information is coming from a magical omniscient black box. The problem with the current lack of transparency is that it often leaves users with the impression that the information they are seeing is objective. In reality, information is being curated to their personal experience by a watchful set of algorithms. Furthermore, algorithms and the people who write them are prone to flaws. Algorithmic transparency increases the probability the users will understand when flaws have been made. We implement it by providing a user with a Relevance Score (R-Score) for each search result, along with the components that determine that R-Score.

Lens modification, by our definition, is the ability for a user to have control over their data stream. For one, a user can choose which profile 'lens' they wish to view information through. Additionally, a user can make adjustments to the R-Score for a given result, thus having more control over their own information bubbles. 

# How

## Methodologies

### Agile Development

  1. Pair Programming

### TDD

## Technologies

Hosted on Heroku

### Testing

  1. RSpec
  2. Capybara

### The Back-End

  1. Ruby on Rails
  2. Ruby/Arachnid2
  3. ElasticSearch
  4. PostgreSQL

### The Front-End

  1. DJavaScript/3
  2. JavaScript/React
  3. JavaScript/Redux
  4. HTML5
  5. CSS3

## Features

### Splash Page

![Xeno Splash](https://github.com/Xeno-Life/Xeno/blob/master/Design%20Assets/Artboard%201.png)

#### Search Profile Net

This option is the default feature, where the user's search brings up a spectrum of profiles with their respective, curated results.

#### Straight to Search

This option allows the user to search in the traditional fashion.
The only results that appear will be the ones curated to the user.

#### Neutral Search

This option allows a user to search with a clean slate, without any demographic or search history information
factored in.

#### Random Profile Search

This option allows a user to search from a profile randomly selected from the spectrum of possible profiles.

#### I'm Feeling Curious Button

#### Settings

### Search Profile Vector Map

![Xeno Search Results](https://github.com/Xeno-Life/Xeno/blob/master/Design%20Assets/Artboard%202.png)

#### Vector Map

#### Preview on Hover

When a user searches via the Search Profile Net option, they will get a spectrum of 'bubbles,' each representing a different profile.
A user can hover over any of these bubbles to bring up a preview of the results page for that profile.  

#### Search Profile Favoriting

A user can favorite profiles they come across if they wish to view results from those profiles later on.

#### Search Profile Information

A user can click on a profile to view the profile's demographic information.

### Search Results Page

![Xeno Search Results](https://github.com/Xeno-Life/Xeno/blob/master/Design%20Assets/artArtboard%203.png)

#### R-Score

The R-Score is a metric that indicates how accurately a particular search result fits a user's profile based on the 'relevance algorithm.' It is based on a few components, including demographics (location, age, etc), previously searched/clicked/liked links, as well as friends' activity.


#### Natural Language Algorithm Explanation
