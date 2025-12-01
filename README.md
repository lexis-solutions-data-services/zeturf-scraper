# Zeturf.fr Scraper

![banner](https://i.ibb.co/vCjcq2hW/zeturf.png)

Automate horse racing data extraction from Zeturf.fr, France's premier horse racing betting platform. This powerful scraper collects comprehensive race results, reports, and programme data including race statuses, favorites, and detailed race information across all French and international racecourses. Perfect for horse racing enthusiasts, bettors analyzing race patterns, and researchers studying French horse racing statistics. Get structured data in JSON format with detailed information about race results, favorites beaten, and horses to remember.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/DevbkY3adMTBuoECt-actor-Mhe1RcgyGdyYcufaa-z5tcTekXpx-ac05abe9-zeturf-courses-hippiques.jpg" alt="Zeturf.fr Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/zeturf-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


👋 Welcome to the Zeturf.fr Scraper, an actor designed to help you gather horse racing data from zeturf.fr! With this actor, you can easily extract race results, reports, and programme information from France's leading horse racing platform.

## Introduction

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.11` |
| **Last Update** | Dec 1, 2025 |

---



The Zeturf.fr Scraper is a web scraping tool designed to extract horse racing data from zeturf.fr. It was created to make it easier for horse racing enthusiasts, bettors, and researchers to access and analyze race results, programme data, and racing statistics from France's premier horse racing platform.


## 💻 Integration Examples

This repository includes example code showing how to integrate the `zeturf-scraper` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---


## Use Cases

Here are some typical scenarios in which the Zeturf.fr Scraper can be useful:

- **Horse Racing Enthusiasts** can use the scraper to track race results and analyze performance patterns
- **Bettors** can use the scraper to monitor race outcomes, favorites beaten, and horses to remember for future betting
- **Researchers** can use the scraper to study French horse racing statistics and trends
- **Data Analysts** can use the scraper to build comprehensive databases of French horse racing information

## Input 📥

To use this actor, you need to provide the following input:

- Field: **startUrls**
  - Type: array
  - Required: Yes
  - Description: URLs to start scraping from

```json
{
  "startUrls": [{ "url": "https://www.zeturf.fr/en/resultats-et-rapports" }]
}
```

## Output 📤

An example output looks like this:

```json
{
  "url": "https://www.zeturf.fr/en/resultats-et-rapports",
  "title": "Results & Reports for the races of 9/23/25",
  "extractedAt": "2025-09-23T14:54:10.768Z",
  "summary": {
    "totalProgrammes": 3,
    "totalRaces": 41,
    "racesByStatus": {
      "In progress": 2,
      "Coming soon": 4,
      "Completed": 34,
      "Canceled": 1
    }
  },
  "programmeData": [
    {
      "date": "TUESDAY 23 SEPTEMBER",
      "tableData": [
        {
          "numero": "R3",
          "nom": "VINCENNES",
          "statut": "In progress",
          "nb-courses": "8",
          "next_step": "Results"
        },
        {
          "numero": "R1",
          "nom": "AUTEUIL",
          "statut": "Completed",
          "nb-courses": "8",
          "favoris-battus": "CANNDARIAN, KRISTAL DU SEUIL, OLYMPIC STORY, SAHARIENNE, JACHAR",
          "a-retenir": "SO RISKY, BINISEGARRA, SILVER BUCKLE, PAS DE QUARTIER, KING PINEAU",
          "next_step": "Results"
        }
      ],
      "total": 12
    }
  ]
}
```

## What data can the Zeturf.fr Scraper extract?

The Zeturf.fr Scraper extracts comprehensive horse racing data including:

- **Race Results**: Complete race outcomes with winners and placements
- **Programme Data**: Daily race schedules organized by date and racecourse
- **Race Status**: Current status of races (In progress, Coming soon, Completed, Canceled)
- **Favorites Beaten**: Information about favorite horses that didn't win
- **Horses to Remember**: Notable horses that performed well
- **Race Statistics**: Total programmes, races, and status breakdowns

## Why use the Zeturf.fr Scraper?

- ⚡️ **Fast** - The scraper efficiently handles complex race data and multiple racecourses.

- 🤙 **Easy to use** - Simply input the URL and let the scraper handle the complexities of French horse racing data.

- 🏇 **Comprehensive** - Extracts all available race data including results, favorites, and programme information.

- ☑️ **Well-Maintained** - The scraper is maintained by the Lexis Solutions team, ensuring reliable performance.

## Limitations

- The scraper focuses on the results and reports page structure
- Historical data availability depends on Zeturf.fr's data retention policies

## FAQ 💬

- **What is Zeturf.fr?**

  Zeturf.fr is France's leading online horse racing betting platform, offering comprehensive race data, results, and betting opportunities across French and international racecourses.

- **How can I access race data on Zeturf.fr?**

  You can access race data by visiting zeturf.fr and navigating to their results and reports section. The Zeturf.fr scraper automates this process by extracting all available race data.

- **Can I use the Zeturf.fr scraper for betting purposes?**

  The Zeturf.fr scraper is for data extraction and analysis only. It should not be used for automated betting or to interact with betting systems. Ensure you comply with the terms of service of Zeturf.fr when using this actor.

- **What types of race data can the Zeturf.fr scraper find?**

  The scraper can extract any race data available on the results page, including:

  - Race results and outcomes
  - Programme schedules
  - Race status information
  - Favorites beaten
  - Horses to remember
  - Race statistics and summaries

- **What if the website changes?**

  Website changes may affect the scraper's functionality. In such cases, our team will update the scraper to maintain compatibility. We regularly monitor and maintain our scrapers to ensure reliable operation.

## Need to scrape other horse racing platforms?

Here are some other horse racing and betting platform scrapers you might find useful:

- **France 🇫🇷**

  - [LeTrot Scraper](https://apify.com/lexis-solutions/letrot-com-scraper) - French trotting horse racing data and results

- **Australia 🇦🇺**
  - [Sportsbet Scraper](https://apify.com/lexis-solutions/sportsbet-com-au-scraper) - Comprehensive betting data from Australia's leading sports betting platform

---

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!
