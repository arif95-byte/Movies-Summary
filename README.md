# Introduction
This project is to determine on what factor affect movie ratings:
<p>1. Is the language affect the movies popularity?</p>
<p>2. What genre or themes have the higher ratings?</p>
<p>3. Identify movies with hight ratings but relatively few votes.</p>
<p>4. How movies in different languages are rated? This can reveal culture differences in movie production or audience rating behaviour.</p>

# Insights
![Screenshot 2024-04-22 234448](https://github.com/arif95-byte/Movies-Summary/assets/75437274/463eff3d-7715-4183-a9a0-30c1f67c3f28)
![Screenshot 2024-04-22 234456](https://github.com/arif95-byte/Movies-Summary/assets/75437274/e125cbcc-77f5-45ad-8080-98f1a0eb8f46)
1. The bar plot shows that English is by far the most popular language in terms of total vote counts, followed by other languages such as French, Japanese, and Italian. This indicates that English-language films dominate in terms of audience engagement and popularity in the dataset.
2. The analysis of the most frequent words in movie overviews reveals common themes and elements. Words like "life", "young", "family", and "world" are among the most frequently mentioned. This suggests that themes around personal and global struggles are prevalent in the dataset's films.

![Screenshot 2024-04-22 234507](https://github.com/arif95-byte/Movies-Summary/assets/75437274/5e909876-9391-4c37-aa34-39cc55dcccdc)
1. The visualizations display the top bigrams and trigrams from the movie overviews. These n-grams provide more context about prevalent themes, such as specific relationships or actions frequently mentioned, like "young man", "high school", or "new york city". These phrases give us an insight into common settings or character dynamics in movies.
2. The sentiment scores of the movie overviews have been calculated, where a score close to 1 indicates a positive sentiment, -1 indicates a negative sentiment, and around 0 represents neutral sentiment.
<p>Mean Sentiment: The average sentiment across all movie overviews is slightly positive at approximately 0.040, indicating a generally neutral to slightly positive tone in the movie descriptions.</p>
<p>Sentiment Distribution: The sentiment scores range from -1 to 1, with 25% of the scores being below -0.073, 50% below 0.031 (median), and 75% below 0.167. This shows that while most descriptions tend to be neutral or slightly positive, there are instances of strongly negative and positive sentiments.</p>

![Screenshot 2024-04-22 234529](https://github.com/arif95-byte/Movies-Summary/assets/75437274/b6ab93f4-c0cb-4d47-84e2-5b329178794a)
1. Number of Movies: The bar plot (in light blue) shows that English (en) dominates the dataset with the highest number of movies, followed by other languages like French (fr) and Japanese (ja). This suggests a strong representation of English-language films in the dataset.
2. Average Rating: The line plot (in red) overlays the average ratings for movies in each language. While English-language films are the most numerous, the average ratings are relatively consistent across different languages, with several non-English languages displaying comparable or even higher average ratings.
3. Language Diversity and Quality: Despite the predominance of English, the quality of movies, as indicated by average ratings, is relatively even across many languages. This could indicate that non-English films, though fewer in number, are able to maintain a high quality that matches or exceeds English films in terms of viewer ratings.
4. Potential for International Cinema: The data suggests that there is a broad spectrum of highly rated films in various languages, highlighting the potential value in international cinema. Distributors and streaming services could benefit from tapping into these markets by promoting high-quality non-English content.
5. Cultural Representation: The presence of multiple languages with high average ratings but lower movie counts may indicate niches in the film industry that could be further explored to meet diverse audience interests.

# Conclusion
1. Movies show a wide range of ratings, with a central tendency around a 6.3 average. This indicates a generally moderate level of quality as rated by viewers.
2. English-language films dominate the dataset both in terms of quantity and total vote counts, suggesting a strong focus or availability of English-language content. However, films in other languages also exhibit high quality based on their ratings.
3. There exists a subset of movies that, despite high ratings, have not received a significant number of votes. These could be considered "hidden gems" and might benefit from increased exposure or marketing efforts to reach a broader audience.
4. Common themes include personal and global challenges, reflecting prevalent story arcs involving individual or collective struggles. The sentiment analysis generally showed a neutral to slightly positive tone in movie overviews.

# Challenges
There were some limitations due to missing data fields like release dates, which could have provided insights into trends over time. Additionally, technical constraints in the analysis environment limited some types of text analysis.

# Recommdendations
1. There's an opportunity to promote highly rated but less popular films, particularly those in non-English languages, to cater to niche audiences and enhance content diversity.
2. Leveraging insights from text and title analysis could guide marketing strategies and content recommendations tailored to prevalent themes and popular keywords.
3. Understanding the themes and words that frequently appear in successful movie titles might help in crafting titles that are more likely to engage potential viewers.
