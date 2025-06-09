# Amazon US Fulfillment Center Flipping Checker

This Google Sheets project helps logistics and freight professionals optimize shipments by identifying the closest inter-flippable Amazon Fulfillment Center (FC) within the same zone from a given zip code.

## 🔍 What It Does
- Maps Amazon FCs to their respective zones  
- Uses Google Maps API to calculate distances between shipper’s zip code and FCs  
- Identifies compatible FCs within the same zone that can be used for “flipping”  
- Finds and lists the closest FC to reduce transit time and cost  

## ⚙️ How It Works
- Built with Google Sheets + Google Apps Script  
- Calculates distances and compares all FCs in the same zone  
- Returns the nearest compatible FC and the distance to it  
- Helps reduce transit time (TAT) and improves pricing accuracy  

## 📁 Files
- `flippingChecker.gs` – Google Apps Script code for distance calculations and zone compatibility checks  

## 🚀 How to Use
1. Make a copy of the Google Sheet (link below)  
2. Select the desired Amazon FC from the dropdown  
3. Enter the shipper’s zip code  
4. View the closest flippable FC and its distance  

## 🛠 Tech Used
- Google Sheets  
- Google Apps Script  
- Google Maps API  

## 📌 Notes
- Zones and FC mappings are predefined in the sheet  
- Flipping is only possible among FCs within the same zone  
- Distance calculations use cached results to improve speed and reduce API calls
