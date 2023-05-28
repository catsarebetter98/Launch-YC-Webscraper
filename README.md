# Launch-YC-Webscraper
A randomized webscraper to scrape all the posts from Launch YC (https://www.ycombinator.com/launches).

You'll need to download a headless chrome driver and replace the line
```
webdriver_path = '/Users/hide/Downloads/chromedriver_mac64/chromedriver.exe'
```
with your own path

Run with `python3 run.py`

Example data looks like

```
{
  "vote_count": "",
  "company_name": "Locale",
  "description": "A marketplace for prepared meals from top restaurants",
  "post_date": "2023-05-25T09:14:35-07:00",
  "cohort": "S2021",
  "tags": [
    "S2021",
    "Grocery",
    "Marketplace",
    "Delivery",
    "Food"
  ],
  "link": "https://www.ycombinator.com/launches/IgH-locale-we-re-making-restaurant-delivery-affordable"
}
{
  "vote_count": "",
  "company_name": "Runway",
  "description": "Better mobile build distribution for teams",
  "post_date": "2023-05-24T08:53:19-07:00",
  "cohort": "W2021",
  "tags": [
    "W2021",
    "SaaS",
    "B2B"
  ],
  "link": "https://www.ycombinator.com/launches/IgC-build-distro-by-runway"
}
{
  "vote_count": "",
  "company_name": "Cosmic",
  "description": "Cosmic is an API-first content management system (CMS). We provide a web dashboard to create content, and API tools to deliver content to any website or app. ",
  "post_date": "2023-05-23T10:23:03-07:00",
  "cohort": "W2019",
  "tags": [
    "W2019",
    "Developer Tools",
    "API"
  ],
  "link": "https://www.ycombinator.com/launches/Ifp-cosmic-headless-cms-and-api-toolkit-v2-0"
}
{
  "vote_count": "",
  "company_name": "Mesh Analytics",
  "description": "AI-powered revenue analytics & attribution for B2B businesses",
  "post_date": "2023-05-23T09:05:01-07:00",
  "cohort": "S2022",
  "tags": [
    "S2022",
    "SaaS",
    "B2B",
    "Analytics",
    "Marketing"
  ],
  "link": "https://www.ycombinator.com/launches/IfL-mesh-understand-what-s-driving-revenue-across-marketing-sales"
}
```

[Go here](https://www.pageshidara.com/) if you want [Andy](https://twitter.com/Page_Farms) and [me](https://twitter.com/catsarecuter98) to build build free tools to get traffic to your page.
