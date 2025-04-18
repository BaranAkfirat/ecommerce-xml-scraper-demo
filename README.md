# 🕷️ eCommerce XML Scraper & Generator

This project is a Python-based tool designed to extract product information from e-commerce websites and convert the data into a well-structured XML format. It is primarily used for product integration with platforms like **Trendyol** and **Hepsiburada**.

---

## 🚀 Features

- Automatically scrapes product details including:
  - Product Name
  - Description
  - Price
  - Stock
  - Variants (e.g., size, color)
  - Barcode
  - Product Images
- Supports both single and multiple variant structures.
- Outputs data in a clean XML format compatible with e-commerce integrations.
- Can be extended to handle dynamic content using **Selenium**.

---

## 🛠️ Technologies Used

- Python 3.x
- `requests`, `BeautifulSoup` – for scraping static content
- `xml.etree.ElementTree` – for XML file generation
- Optional: `Selenium` – for dynamic JavaScript-based pages

---

## 🔐 Source Code Access

This repository is private and not publicly accessible.
If you are interested in a demo or collaboration, feel free to reach out.
- 📧 Email: baranakf@gmail.com

## ⚠️ Disclaimer

This project is intended for legal, ethical, and permitted use only.
Always respect the terms of service and scraping policies of target websites before using this tool in production.

## 📂 Sample XML Output

```xml
<Product>
  <ProductName>Basic T-Shirt</ProductName>
  <Price>179.99</Price>
  <Stock>25</Stock>
  <Variants>
    <Variant>
      <Color>Black</Color>
      <Size>M</Size>
      <Barcode>1234567890123</Barcode>
    </Variant>
  </Variants>
</Product>

