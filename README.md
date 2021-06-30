# DigHum-100-Project
This is my project for DigHum 100 (Theory & Methods in the Digital Humanities) @ UC Berkeley in summer 2021 taught by Prof. Adam Anderson.
This notebook is an introductory data analysis of BTS's worldwide critical acclaim. We will take three theories that is widely believe by many about BTS's ascendancy from the media and take those claims back to the data..<br/><br/>

The dataframe `lyrics` contains 226 observations of BTS tracks and includes `album_title`, `track_title`, `lang` (the language of the song) and, most importantly, `lyrics` as features. This dataframe is provided by Kaggle user **kaili** who scraped this data from https://genius.com/  under a **CC0: Public Domain License**.
<br/><br/>

The dataframe `spotify` is also a Kaggle dataset by user **Yamac Eren Ay** who, by using the Spotify API, has scraped data from about around 600,000 tracks published on Spotify under **Community Data License Agreement – Sharing, Version 1.0**. 
<br/><br/>

*Note that the "full" dataset has over 15 million tracks and includes data about specific artists, but is over 3GB in storage.* 
<br/><br/>

This dataset provides information on easily gathered features such as `popularity` and `duration_ms`, but also Spotify measures their own audio features such as `danceability`, `energy`, `key`, `loudness`, `mode` and much more. 
The full description of these features can be found at https://developer.spotify.com/documentation/web-api/reference/#category-tracks under AudioFeaturesObject.

We will also be using another Kaggle dataset from user **Deep Shah** on the lyrical content of popular American artists. (Full list and data import can be found in Data Cleaning). It is published under a **CC0: Public Domain License**.

The final sets of data we will be using popular search engines. Google offers a service named [Google Trends](https://trends.google.com/trends/) that offers users quantitative data about the popularity of a search term, separated by country. Naver, the South Korean equivalent of Google, also offers a similar service, [Naver DataLab](https://datalab.naver.com/). *(Beware: Naver is a Korean site, but Google Translate should perform adequately here.)*<br/><br/>

This project looks at 3 theories on BTS's ascendency to a household name.

[This](https://lucid.app/lucidchart/invitations/accept/inv_4a7d3188-c38e-494a-99b4-4087b663c3e4?viewport_loc=-31%2C663%2C1157%2C532%2C0_0) is a link to the full storyboard which includes full documentation about the data analysis process.
