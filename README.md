# Weekly Oil Bulletin Database

This repository contains the collated price data of petroleum products across EU countries and the UK, which is published in the Weekly Oil Bulletin through the European Commission.  
More information on the bulletin can be found here: [https://energy.ec.europa.eu/data-and-analysis/weekly-oil-bulletin_en]()

## Database

The data is stored in [data/db](), with a two identical files - one in binary (`.rds`) and in text (`.csv`) formats.
Both files have identical contents.

## Method

The bulletin is released as a PDF file containing a list of weekly bulletins.
Based on the PDF and publishing dates, download links for individual bulletins are created, downloaded and re-formatted for storing in the database.
A central log file tracks the status of downloads and data base creation, and is updated on each run.

## Latest update:

Date: Feb 14, 2023