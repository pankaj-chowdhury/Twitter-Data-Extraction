# Twitter Data Extraction
📢 Exciting Twitter data analysis using Python's Twarc and Pandas! 🚀

I've been exploring Python's powerful tools to fetch and analyze Twitter data, and I'm amazed by the possibilities! 🐍🐦

In this project, I used the Twarc library to search for tweets with the hashtag #ManipurViralVideo. 📅 I then extracted relevant data and saved it into a JSON file.

Here's a summary of the code:

1. Import required libraries:
   - gzip: For handling gzip-compressed data.
   - json: For working with JSON data.
   - pandas: For data manipulation and analysis.
   - datetime: To work with dates and times.
   - tqdm: For a neat progress bar to keep track of data retrieval.
   - twarc: A fantastic library to interact with the Twitter API.

2. Set up Twarc:
   I created a Twarc instance using my Twitter API credentials to access Twitter data.

3. Define the hashtag and date range:
   I specified the hashtag #ManipurViralVideo and calculated the date range to search for tweets within the last 10 days.

4. Fetch and save relevant tweets:
   I filtered tweets containing the hashtag and saved them along with their creation times to a list.

5. Create a DataFrame for analysis:
   Finally, I converted the list of tweets into a Pandas DataFrame, which will make data analysis a breeze! 📊

Python, combined with Twarc and Pandas, made it effortless to process Twitter data efficiently. Now, I can dive into exciting insights and trends related to #ManipurViralVideo. 📈

🤝 Happy coding and data exploration! 🚀💻
