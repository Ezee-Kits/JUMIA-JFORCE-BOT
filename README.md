# ⚡ JUMIA JFORCE BOT — Complete Multi-Platform Product Scraping & Posting Automation

## 🧠 Overview
**JUMIA JFORCE BOT** is a **fully automated Python-based system** that empowers e-commerce sellers, marketers, and social media managers to **scrape, manage, and post products effortlessly**. This automation covers every step of product management and posting, from extracting product information on **Jumia Nigeria** to publishing posts on multiple social media platforms including **Facebook, Facebook Marketplace, Instagram, and Twitter/X** — all with minimal human intervention.  

Whether you want to streamline your e-commerce operations, grow your social media presence, or automate repetitive posting tasks, **JUMIA JFORCE BOT** handles it end-to-end, making your workflow faster, smarter, and scalable.

This project was developed by **Ezee Kits**, and I’ve created a **detailed step-by-step video tutorial** on my **[YouTube Channel (Ezee Kits)](https://www.youtube.com/@Ezee_Kits)** that explains:  
- How to set up Python and all dependencies  
- How to scrape products from Jumia intelligently  
- How to automate posting on multiple social media platforms efficiently  
- Best practices for organized file storage and product management  

---

## 🎯 Key Features
**JUMIA JFORCE BOT** automates your workflow across three main areas:  

1. **URL Collection (`ALL URLS`)**
   - Scrapes all product URLs from Jumia’s homepage and category pages  
   - Saves URLs in a structured CSV file for tracking, management, and reuse  

2. **Product Information Management (`PRODUCT`)**
   - Extracts comprehensive product data, including:  
     - Name, brand, price (₦), description, specifications, key features  
     - Seller information, production date, item number, and more  
   - Downloads and stores product images automatically  
   - Maintains organized CSV files per product for structured data storage  

3. **Automated Social Media Posting (`PY FILES`)**
   - `main.py` → Scrapes product data from Jumia and stores it  
   - `facebook.py` → Automates posting products on Facebook  
   - `facebook_marketplace.py` → Automates posting products on Facebook Marketplace  
   - `instagram.py` → Automates posting products on Instagram  
   - `twitter.py` → Automates posting products on Twitter/X  
   - `POSTING_BOT.py` → Orchestrates all posting operations and acts as the “ON switch” for full automation  

Additional features include:  
- Randomized URL and product selection for diversity  
- Clipboard automation to ensure proper formatting of posts  
- Automated browser tab management to handle multiple platforms simultaneously  
- Logging and CSV management for monitoring every posted product  

---

## ⚙️ Setup Guide

### Step 1: Install Python
Ensure **Python 3.10+** is installed on your system.  
```bash
python --version


📦 Step 2: Install Required Libraries
pip install pyppeteer pandas beautifulsoup4 requests asyncio pyperclip


If pyppeteer fails, try:

pip install pyppeteer==2.0.0


⚡ Step 3: Install Chrome or Chromium

Required for Pyppeteer to run browser automation

Ensure your Chrome profile is cloned for smooth automation


🧮 Step 4: Clone the Project
git clone https://github.com/yourusername/JUMIA-JFORCE-BOT.git
cd JUMIA-JFORCE-BOT


▶️ Step 5: Run the Bot
python POSTING_BOT.py


The script will:

Scrape URLs from Jumia

Collect random product information

Open browser tabs for Facebook, Instagram, Twitter/X, and Facebook Marketplace

Automatically post products with descriptions, specifications, and images

💻 Folder Structure
JUMIA JFORCE BOT
│
├── ALL URLS            # Stores CSV files of all scraped product URLs
├── PRODUCT             # Stores product CSVs and downloaded images
└── PY FILES            # Contains all Python scripts:
    ├── main.py
    ├── facebook.py
    ├── twitter.py
    ├── instagram.py
    ├── facebook_marketplace.py
    └── POSTING_BOT.py

🧠 How It Works (Step-by-Step)

Scrapes product URLs from Jumia homepage and category pages

Selects random or specific URLs to scrape product data

Collects all product details including:

Name, brand, price, key features, specifications, images, bag info, seller info, production date

Saves all data into structured CSV files and downloads images

Opens browser tabs using Pyppeteer

Posts products on Facebook, Instagram, Twitter/X, and Facebook Marketplace

Logs progress automatically and repeats posting continuously

🔍 Example Output

CSV Example (PRODUCT/product123.csv):

NAME,BRAND,PRODUCT_PRICE,NAIRA_PRICE,KEY_FEATURES,SPECIFICATION,BAG_INFO,SELLER_INFO,PRODUCT_PIC_URLS
Samsung Galaxy S23,Samsung,450000,₦450,000,['Feature1','Feature2'],['Spec1','Spec2'],0,['Seller1'],[['path/pic_0.jpg','path/pic_1.jpg']]


Automated Post Example (Facebook / Instagram / Twitter):

💥 Samsung Galaxy S23 💥
PRICE : ₦450,000

➡️  KEY FEATURES
- Feature1
- Feature2

⚙️  SPECIFICATION
- Spec1
- Spec2

📦 CONDITION : BRAND NEW
👉 Pay After Delivery Available

Chat Up Now!! 📞 CALL OR WHATSAPP @ 09027794130

| Component                | Description                                                                 |
| ------------------------ | --------------------------------------------------------------------------- |
| **Language**             | Python 3.10+                                                                |
| **Automation Engine**    | Pyppeteer                                                                   |
| **Web Scraping**         | BeautifulSoup4, Requests                                                    |
| **Data Processing**      | Pandas, CSV                                                                 |
| **Clipboard Automation** | Pyperclip                                                                   |
| **File Storage**         | CSV & Images                                                                |
| **Libraries Used**       | asyncio, os, random, pandas, requests, beautifulsoup4, pyppeteer, pyperclip |



📱 Advantages

Fully automated multi-platform product posting

Handles images, text, and specifications automatically

Randomized scraping for diverse product posting

Efficient and scalable for e-commerce stores or social media marketing



🎥 Full Video Tutorial

I’ve created a complete walkthrough explaining:

How to scrape Jumia products

How to run the posting bot

How to automate multiple social media platforms

👉 Watch it on YouTube: Ezee Kits Channel 
https://www.youtube.com/channel/UCbDQmSOu4XR64-_1BtJ97TQ

👨‍💻 Author
Ezee Kits (Peter)
🎓 Electrical and Electronics Engineer | 🇳🇬 Nigeria
💡 Passionate about Automation, AI, and E-commerce
📧 Email: ezeekits@gmail.com

📺 YouTube: Ezee Kits
YOUTUBE LINK:  https://www.youtube.com/channel/UCbDQmSOu4XR64-_1BtJ97TQ


📜 License

MIT License

This project is free and open-source for educational and research purposes.
Modify or distribute with proper credit to the author.



GitHub Short Description (SEO Optimized):

Full automation bot to scrape Jumia products and post automatically on Facebook, Instagram, Twitter/X, and Facebook Marketplace using Python and Pyppeteer.
