# Customer-Segmentation
# Use Case
## Use Case Summary
## Objective Statement:
- Dapatkan wawasan bisnis tentang berapa banyak produk yang terjual setiap bulan
- Dapatkan wawasan bisnis tentang berapa banyak pelanggan menghabiskan uang mereka setiap bulan.
- Dapatkan wawasan bisnis tentang Kota Pelanggan dan mana yang merupakan pembelanja terbaik secara keseluruhan
- Dapatkan wawasan bisnis tentang Produk Berbeda yang Dijual dan distribusi harganya
- Dapatkan wawasan bisnis tentang Jam berapa saja yang ramai berkunjung ke supermarket
## Challenges:
- Ukuran data yang besar, tidak dapat dikelola oleh spreadsheet excel.
- Perlu beberapa koordinasi dari masing-masing departemen.
- Data demografi memiliki banyak nilai yang hilang dan salah ketik.
## Methodology / Analytic Technique:
- Descriptive analysis
- Graph analysis
- Segment Analysis
## Business Benefit:

- Helping Business Development Team to create product differentiation based on the characteristic for each customer.
- Know how to treat customer with specific criteria.

## Expected Outcome:
- Ketahui berapa banyak produk yang terjual setiap bulannya.
- Tahu berapa banyak pelanggan menghabiskan uang mereka setiap bulan.
- Analisis segmentasi pelanggan.
- Rekomendasi berdasarkan segmentasi pelanggan.

## Business Understanding
- Ritel adalah proses penjualan barang atau jasa konsumen kepada pelanggan melalui beberapa saluran distribusi untuk mendapatkan keuntungan.- Kasus ini memiliki beberapa pertanyaan bisnis menggunakan data:
- Berapa banyak produk yang terjual setiap bulan?
- Berapa banyak pelanggan menghabiskan uang mereka setiap bulan?
- Bagaimana dengan analisis segmentasi Pelanggan?
- Bagaimana dengan rekomendasi berdasarkan segmentasi pelanggan?

## Data Understanding
Data of Retail Transaction from 01 December 2010 to 09 December 2011
Source Data. Supermarket sales. https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales
The dataset has 8 columns and 541909 rows.

Data Dictionary:
- Invoice id: Computer generated sales slip invoice identification number
- Branch: Branch of supercenter (3 branches are available identified by A, B and C).
- City: Location of supercenters
- Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.
- Gender: Gender type of customer
- Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel
- Unit price: Price of each product in $
- Quantity: Number of products purchased by customer
- Tax: 5% tax fee for customer buying
- Total: Total price including tax
- Date: Date of purchase (Record available from January 2019 to March 2019)
- Time: Purchase time (10am to 9pm)
- Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)
- COGS: Cost of goods sold
- Gross margin percentage: Gross margin percentage
- Gross income: Gross income
- Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)

## Data preparation
Code Used:
Python Version: 3.7.6
Packages: Pandas, Numpy, Matplotlib, Seaborn, Sklearn, and Feature Engine
