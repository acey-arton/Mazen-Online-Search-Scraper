
# Mazen Online Search Scraper
>This tool helps you collect structured product data from Mazen Online using your own search terms. It’s built for people who need fast, reliable access to pricing, product details, and marketplace insights without manually browsing the site.



<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Mazen Online Search Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
The Mazen Online Search Scraper takes a list of keywords and automatically gathers matching product results from mazenonline.com. It’s perfect for e-commerce analysts, data teams, and businesses looking to track competition, monitor prices, or build product datasets.

### Why This Scraper Is Useful
- Automates product discovery based on your search terms.  
- Provides structured data ready for Excel, dashboards, or APIs.  
- Supports pricing insights and product comparison at scale.  
- Ideal for recurring market research and competitive tracking.

---
## Features
| Feature | Description |
|---------|-------------|
| **Keyword-Based Search** | Submit one or many search terms to capture all relevant products. |
| **Detailed Product Extraction** | Captures titles, prices, images, descriptions, and availability. |
| **High-Performance Engine** | Optimized for fast scraping with minimal delays. |
| **Structured Output** | Clean JSON and optional Excel downloads. |
| **Scalable Workflow** | Designed for long lists of keywords and large result sets. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|------------------|
| keyword | The search term that generated the product result. |
| productId | Unique product identifier if available. |
| title | Product title as shown on Mazen Online. |
| price | Extracted final price. |
| originalPrice | Pre-discount or reference price. |
| imageUrl | Main product image URL. |
| description | Short product description. |
| url | Product detail page link. |
| availability | Indicates whether the product is in stock. |

---
## Example Output
    
    [
      {
        "keyword": "laptop",
        "productId": "MN12345",
        "title": "Gaming Laptop Pro 16",
        "price": 899.99,
        "originalPrice": 1049.99,
        "imageUrl": "https://mazenonline.com/images/product12345.jpg",
        "description": "High-performance laptop ideal for gaming and work.",
        "url": "https://mazenonline.com/product/12345",
        "availability": "In Stock"
      }
    ]

---
## Directory Structure Tree
    
    Mazen Online Search Scraper/
    ├── src/
    │   ├── main.js
    │   ├── scrapers/
    │   │   ├── search_scraper.js
    │   │   └── product_parser.js
    │   ├── utils/
    │   │   ├── paginator.js
    │   │   ├── normalizer.js
    │   │   └── excel_exporter.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   └── sample_output.json
    ├── outputs/
    │   └── sample.xlsx
    └── README.md

---
## Use Cases
- **E-commerce Analysts** monitor pricing trends across categories.  
- **Online Retailers** benchmark competitors’ product offerings.  
- **Market Researchers** measure inventory availability and product variety.  
- **Price Monitoring Tools** feed updated datasets into dashboards or alerts.  
- **Developers** integrate product search automation into applications or APIs.

---
## FAQs

**Can I search multiple keywords at once?**  
Yes. Submit an array of terms and the scraper processes them sequentially or in parallel based on configuration.

**Does it work with large result sets?**  
It’s optimized for bulk querying and handles long keyword lists efficiently.

**What formats can I download?**  
JSON and Excel are available for export.

**Does it scrape product details or only listings?**  
It captures both listing-level and detailed product information when accessible.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Efficient scraping pipeline completing hundreds of products per keyword in minutes.

**Reliability Metric:**  
High success rates on repeated runs, with automatic retries on failed requests.

**Efficiency Metric:**  
Optimized pagination and request batching reduce unnecessary page loads.

**Quality Metric:**  
Consistent field mapping ensures clean, analysis-ready product records across all keywords.





---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>
