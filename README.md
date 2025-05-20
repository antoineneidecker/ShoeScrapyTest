# 👟 Shoe Scraper: Multi-Brand Shoe Data Collection with Scrapy

This project is a collection of **Scrapy spiders** designed to crawl and extract structured shoe data from a wide range of major and niche footwear brands. The goal is to compile a clean dataset for powering a future **recommendation system** based on user preferences.

---

## 🗂️ Overview

Footwear is deeply personal and highly varied — brand, sport, style, and fit all influence buyer preferences. To build a meaningful recommendation engine, I first needed a diverse and rich dataset of available shoes across many brands.

This project scrapes and compiles that data automatically using custom Scrapy spiders, with **lightweight threading optimizations** to handle concurrent requests efficiently.

---

## 🏷️ Brands Covered

Spiders currently target product pages from the following brands:

- Nike
- Adidas
- New Balance
- Asics
- Puma
- Under Armour
- North Face
- Timberland
- Skechers
- Merrell
- Saucony
- Reebok
- Brooks
- Fila
- K-Swiss
- Converse
- Li-Ning
- Po-Zu
- Mizuno
- Newton
- Apex
- Umbro
- Etonic
- Veja
- Ethletic
- Salomon
- Hoka One One
- Altra
- Syou
- Spira

*...and more to come.*

---

## 📦 Data Fields Collected

Each shoe entry contains the following structured data:

- **Name** – Product title
- **Brand** – Brand identifier
- **Division** – Men / Women / Kids / Unisex
- **Category** – e.g., Running, Soccer, Basketball, Lifestyle
- **Price** – Current price (USD where available)
- **Image URL** – Direct link to product image

---

## ⚙️ Tech Stack

- **Python 3.10+**
- **Scrapy** – Framework for writing crawling logic
- **Threading** – Optimized performance for slower sites
- **Pandas** – For optional structured output
- **JSON/CSV** – Export formats for raw data

---

## 🚀 Use Case

The scraped dataset will be used to build a **personalized shoe recommendation system**, where users can:
- Like or dislike certain shoes
- Receive suggestions based on brand, category, or visual similarity
- Explore a catalog across many brands, unified in one format
