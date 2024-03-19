# Sentiment Analysis for Linkedin posts using transformers + Web Crawler

This project is meant to use AI tools (Natural Language Processing, Sentiment Analysis, Regression models, etc) to **analyse data** around the NFTs industry, Web3 and the luxury brands market on the internet / social media to get:

- ❤️  Sentiment analysis of tweets, posts, blogs,  or videos around our industry and even our competition
- 📈  Detect emerging trending topics, technologies, and market dynamics on the web community towards our industry (NFT, Luxury, Web3)
- 👁️ Monitor reputation of our product

Applications - with the set goal to leverage Arianee by providing valuable data to:

- Keep Arianee updated on the emerging trends, topics  and reputation around our product
- Provide sentiment information to the the C-level executives, sales, marketing, delivery, and product teams in order to improve our operations and strategies in general
- Improve our relationship or delivery to our clients
- Strong understanding of the market
- By integrating AI in Arianee, we can call the attraction of investors to keep them interested in the Arianee project

This model could be scalable and re-used seasonally to keep the business updated.

## Technologies used

**Natural Language Processing (NLP) for Sentiment Analysis:**

**Crawlers**

**Transformers**

## Steps of implementation
First stage
1. Build an automated web crawler with Selenium and BeautifulSoup to extract the texts and descriptions of posts in Linekdin
2. Clean and explore this raw descriptions  and structure them
3. Pre-process the data NLP
4. Apply transformer tokenizers
5. Test different transformer models

Second stage
1. Label data
2. Train our own model
3. Deploy model with dagster

