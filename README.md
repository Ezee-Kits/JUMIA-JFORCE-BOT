⚡ JUMIA JFORCE BOT — Full Product Posting Automation for E-commerce & Social Media

🧠    Overview

JUMIA JFORCE BOT is a complete Python automation system that automatically:

Scrapes products from Jumia Nigeria

Collects all relevant product information (name, price, description, images, model, specifications, seller info, production date, etc.)

Posts products automatically on Facebook, Facebook Marketplace, Instagram, and Twitter (X)

Manages URLs, product data, and posting in an organized folder structure

This bot runs directly on your computer or server using Python and Pyppeteer, automating your e-commerce workflow without manual posting.

This project was developed by Ezee Kits, and I’ve created step-by-step video tutorials on my YouTube Channel (Ezee Kits)
 explaining:

How to set up Python and required libraries

How to scrape products from Jumia

How to automate posting to multiple social media platforms

🎯 What It Does

The bot simplifies product posting by combining:

URL Scraping (ALL URLS folder)

Collects all product URLs from Jumia

Saves them in CSV for tracking and reuse

Product Data Collection (PRODUCT folder)

Scrapes product name, price, brand, description, specifications, images, seller info, and more

Stores data in structured CSV files for each product

Downloads all product images automatically

Social Media Posting (PY FILES folder)

main.py: Scrapes Jumia and gathers product information

facebook.py: Automates posting to Facebook

facebook_marketplace.py: Automates posting to Facebook Marketplace

instagram.py: Automates posting to Instagram

twitter.py: Automates posting to Twitter/X

POSTING_BOT.py: Orchestrates all posting operations, acting as the “ON switch” for automation

All of this runs fully automated, allowing you to post products without manual effort, even across multiple platforms at once.

⚙️ Setup (Python + Pyppeteer Installation Guide)

Follow these steps to get started:

🖥️ Step 1: Install Python

Ensure Python 3.10+ is installed.

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
