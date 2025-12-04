# 🎙️ We're Here to Help — Podcast Analytics Project  
### *A full end-to-end data pipeline using R, SQL, and Tableau*

This project extracts, cleans, structures, and visualizes data from **236 episodes** of the *We're Here to Help* podcast (Stanger & Kulap).

It demonstrates skills in:
- **Web Scraping (R + rvest)**
- **Data Cleaning (R, SQL)**
- **Relational Modeling**
- **Data Visualization (Tableau)**
- **Brand-matching design (custom color palette & typography)**

---

## 🚀 Project Overview

### **1. Web Scraping**
R scripts automatically scrape each episode page, collecting:
- Episode titles  
- URLs  
- Caller names & locations  
- Call reasons  
- Full transcripts  
- Guest names parsed from titles  

### **2. Data Cleaning (SQL + R)**
Processed into three master tables:
- `episodes_master.csv`
- `callers_master.csv`
- `transcripts_master.csv`

Cleaning steps include:
- Duplicate removal  
- Broken episode fixes (166–215 missing segments repaired)  
- Guest extraction from titles  
- Multi-caller episode expansion  

---

## 📊 Tableau Dashboard  
**Live dashboard:** *(Add Tableau Public link here)*

The dashboard uses a **custom WHtH blue/yellow color palette** and includes:

- Episode browser  
- Call volume analysis  
- Guest insights  
- Caller locations  
- Topic frequency  
- Timeline trends  

Palette file included: `tableau/palette/WHtH_ColorPalette.tds`

---

## 📁 Repository Structure

### `data/`
Contains raw scraped transcripts and cleaned CSV outputs.

### `code/`
All R and SQL scripts used to generate the dataset.

### `tableau/`
Final dashboard (`.twbx`) + brand palette + screenshots.

### `branding/`
Color palette files & extracted brand hex values.

### `docs/`
Diagrams and notes on pipeline architecture.

---

## ⚙️ Technologies Used
- **Python** (Colab, )
- **R** (rvest, xml2, dplyr, purrr)
- **SQL** (Cleaning + joins)
- **Tableau** (Branded interactive dashboard)
- **GitHub** (Version control + documentation)

---

## 📬 Contact
If you'd like to discuss this project or similar analytics work:  
**Ken Johnson — Data Analytics & Workforce Optimization**  
📧 *kenjohnson@live.ca*  
🔗 *linkedin.com/in/ken-johnson-69731196*

