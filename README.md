PROJECT FILMWORKS: MICROSOFT’S NEW MOVIE STUDIO INITIATIVE

Overview: Creating Microsoft's Movie Studio.

Microsoft, a global technology leader renowned for its innovations in software, hardware, and cloud computing, is venturing into the realm of entertainment. Recognizing the transformative power and financial potential of the film industry, Microsoft is poised to create its own movie studio. This strategic pivot represents a significant step in Microsoft's journey toward diversification and expansion beyond its traditional technology domains.
The entertainment sector, which includes aspects like film production, distribution, and content creation, is a domain marked by creativity, captivating audience interactions, and constant technological advancements. As Microsoft makes its entry into this field, the company seeks to capitalize on its technological prowess, maximize its substantial resources, and actively participate in the ever-evolving world of cinema. This move into movie studio operations closely aligns with Microsoft's dedication to delivering top-notch, culturally impactful content to a worldwide audience.
This project aims to provide Microsoft with essential insights and strategies required to establish a successful movie studio. By conducting a thorough analysis of the film industry, identifying trends, and understanding audience preferences, the project seeks to equip Microsoft with the knowledge needed to make informed decisions in this dynamic and competitive domain. In doing so, it sets the stage for Microsoft's entry into the world of cinema with a clear vision and a strong foundation for success.

Business understanding

The move to join the movie industry reflects Microsoft's recognition of the transformative power of storytelling, the widespread appeal of cinematic content, and the immense financial potential that this industry offers. Building upon its robust technological infrastructure and resources, Microsoft is strategically positioned to harness these assets and create a profound impact within the realms of film production, distribution, and content creation.
The movie industry involves producing a wide array of content, from blockbuster films to compelling documentaries and captivating series. Microsoft's venture into this domain aligns with its broader mission of enhancing the lives of individuals and organizations through innovation. 

The objectives 

•	To analyze the overall box office performance of movies, including domestic, foreign gross and budget, to identify trends and patterns over the years.

•	To identify emerging genre trends by analyzing the popularity of genres over time.

•	To analyze movie details such as directors and box office performance, to be able to see directors who have produced more movies over the years.

•	To analyze relationship between reviews and ratings.

Data understanding

In this project, we'll work with a bom.movie_gross.csv, ‘rt.movie_info.tsv’, ‘tmdb.movies.csv’, ‘im.db’ database, ‘rt.reviews.tsv’ and tn.movie_budgets.csv datasets. Because they were collected from various locations, the different files have different formats. Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software or pd.read_csv, while the data from IMDB is located in a SQLite database.

These are the datasets we will work with to analyze our data:

•	'bom.movie_gross.csv' has columns ('title', 'studio', 'domestic gross', 'foreign gross', 'year')

•	'tn.movie_budgets.csv' has columns (id, release date, movie, production budget, domestic gross, worldwide gross)

•	'tmdb.movies.csv' has columns (genre ids, id, original language, original title, popularity, release date, title, vote average, vote count)

•	movie_ basics from im.db database has columns (movie id, primary title, original title, start year, runtime minutes, genres)

•	'rt.movie_info.tsv' has columns (id, synopsis, rating, genre, director, writer, theatre date, dvd date, currency, box office, runtime, studio)

•	'rt.reviews.tsv’ has columns (id, review, rating, fresh, critic, top critic, publisher, date)

Here we start by cleaning our datasets the ones we will be using for data analysis.

1: Looking for missing values in rows and deciding whether to remove them by dropping missing rows or by imputing either by mean, median or mode if need be.

2. Looking for duplicates.

We start by:

Data Analysis

We can start performing our analysis using Exploratory Data Analysis (EDA) using a python library called pandas.

Then represent our analysis by data visualization:

These are the graphs we came up with to answer the objectives:

1.	To analyze the overall box office performance of movies, including domestic, foreign gross and budget, to identify trends and patterns over the years.
  ![image](https://github.com/rizzyakoth/dsc-phase-1-project-v2-4/assets/142317233/a7205cf3-7b1b-42a6-ad25-3be13bf244de)

2.	To identify emerging genre trends by analyzing the popularity of genres over time.
  ![image](https://github.com/rizzyakoth/dsc-phase-1-project-v2-4/assets/142317233/09519a03-6d20-4df7-b8de-c7b70268b081)

3.	To analyze movie details such as directors and box office performance, to be able to see directors who have produced more movies over the years.
 ![image](https://github.com/rizzyakoth/dsc-phase-1-project-v2-4/assets/142317233/032bd657-a3b9-4b24-a1ad-d3b6c1795ec9)
 ![image](https://github.com/rizzyakoth/dsc-phase-1-project-v2-4/assets/142317233/e7043d35-272f-40ee-8853-aa48ad621846)
 4.	To analyze relationship between reviews and ratings.
  ![image](https://github.com/rizzyakoth/dsc-phase-1-project-v2-4/assets/142317233/8a1a491e-a58f-4f8b-b5d7-55e25ea9bf01)

Recommendation

Based on our analysis, we can draw the following recommendations:

1.	Quality Assurance and Improvement: Place a strong emphasis on ensuring the quality of your movies. Positive reviews and high ratings are often correlated with well-made, engaging films. Invest in scriptwriting, production, and post-production to create movies that captivate both critics and audiences.

2.	International Market Expansion: Given that you're analyzing both domestic and foreign box office performance, consider strategies to tap into international markets. Identify genres and trends that resonate with global audiences. Collaborate with international distribution partners and explore localization options to enhance your movie's appeal in different regions.

3.	Diversify Genre Portfolio for Better Box Office Performance: Based on our analysis of genre trends, consider diversifying the movie portfolio. Invest in genres that are currently on the rise to maximize box office potential. Keep an eye on emerging genres and be prepared to adapt your production strategy to meet changing audience preferences.

4.	Director Selection and Performance: Utilize insights from your analysis of director performance and box office results to make informed decisions when selecting directors for your projects. Consider collaborating with directors who have a track record of delivering successful movies in genres that align with your objectives.

Next Step

It's important to note that the movie industry is ever-evolving, and staying attuned to ongoing changes and innovations is essential for continued success in this dynamic field.

The movie industry is highly competitive and subject to evolving trends, so staying proactive and adaptable is crucial. Regularly revisiting and updating your analysis will help ensure its continued relevance and effectiveness in guiding decision-making for the movie studio.

[Index - Jupyter Notebook.pdf](https://github.com/rizzyakoth/dsc-phase-1-project-v2-4/files/12645947/Index.-.Jupyter.Notebook.pdf)
