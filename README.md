# Block AI with `robots.txt`

This is a community-built collection of robots.txt entries to ask AI services from scraping your sites content.

```
User-agent: CCBot
Disallow: /

User-agent: ChatGPT-User
Disallow: /

User-agent: GPTBot
Disallow: /

User-agent: Google-Extended
Disallow: /

User-agent: Omgilibot
Disallow: /

User-agent: FacebookBot
Disallow: /

User-agent: Amazonbot
Disallow: /
```

## About robots.txt

`robots.txt` is a file that web crawlers _may choose_ to use to determine which parts of your website, if any, they can scrape. Many people use this to control which parts of their site a search engine will index.

**Importantly, however, robots.txt is merely a polite suggestion to the crawler.** Many web scraping services and tools do not honor robots.txt, including some AI services.

## Credits

- [Patrick Samphire on Mastodon](https://mastodon.social/@patricksamphire@wandering.shop/111147479365809824)
