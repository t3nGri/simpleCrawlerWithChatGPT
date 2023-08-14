# simpleCrawlingWithChatGPT
I wrote a simple python script to extract information and images from a Chinese e-commerce website that has unstable information. Script uses ChatGPT api to create more data and categorize gotten informations. Lastly, it creates the CSV file to import products for WooCommerce / WordPress.

# Features
- Extract Informations
- Extract Images
- Optimize Images with Pillow
- Creates new information with chatGPT like description text
- Categorize extracted informations
- Creates CSV file to upload products to WooCommerce

# Why I used Selenium to extract information instead of bs4?
The website(Yupoo) has a well-structured security for crawling. The only way to surf between information and images was by doing it manually.
