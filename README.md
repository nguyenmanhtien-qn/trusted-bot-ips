# TrustedBotIPs

**TrustedBotIPs** is a project designed to store and manage lists of IP addresses of trusted bots. The goal of this project is to provide a centralized database that makes it easy to track and validate legitimate bots crawling data from trusted services.

## Description

This project provides a well-organized directory structure to store bot IP lists. Each bot source has its own folder, with each source having a `.txt` file containing the list of IPs. Additionally, an aggregated file outside the source-specific folders will store all bot IPs in one place for easy access and use.

### Daily Updates

The lists of trusted bots will be **updated daily**, with frequent updates to include the most common and popular bots in use today. This ensures that the database remains current and reliable.

### Supported Bots

The following bots are included in this project, categorized by their respective sources:

| Bot Name            | Description                |
|---------------------|----------------------------|
| ahrefsbot           | Ahrefs bot for SEO analysis |
| applebot            | Apple's web crawler        |
| baidubot            | Baidu search engine bot    |
| bingbot             | Bing search engine bot     |
| bravebot            | Brave browser bot          |
| cloudflarebot       | Cloudflare's bot           |
| coccocbot           | Cốc Cốc search bot         |
| datadogbot          | Datadog monitoring bot     |
| discordbot          | Discord bot                |
| duckduckgobot       | DuckDuckGo search bot      |
| facebookbot         | Facebook bot               |
| googlebot           | Google search bot          |
| huaweibot           | Huawei bot                 |
| linkedinbot         | LinkedIn bot               |
| naverbot            | Naver search bot           |
| openaibot           | OpenAI bot                 |
| perplexitybot       | Perplexity bot             |
| pinterestbot        | Pinterest bot              |
| semrushbot          | SEMrush bot                |
| seznambot           | Seznam search bot          |
| skypeuripreviewbot  | Skype URL preview bot      |
| sogoubot            | Sogou search bot           |
| telegrambot         | Telegram bot               |
| twitterbot          | Twitter bot                |
| yahoobot            | Yahoo search bot           |
| yandexbot           | Yandex search bot          |

### Bot Classification

For easier management and use, the bot IPs are categorized into two main files:

- **seo_bots_cidrs.txt**: Contains the IPs of bots related to SEO, including popular search engine bots.
- **all_bots_cidrs.txt**: Contains the IPs of all other bots not directly related to SEO but are trusted and legitimate.

These files help streamline the process of distinguishing between SEO bots and other types of bots while maintaining a centralized source for all bot IPs.
