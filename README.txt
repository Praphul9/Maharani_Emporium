═══════════════════════════════════════════════════════
  MAHARANI EMPORIUM — Website Package
  1417a Gerrard St E, Toronto, ON M4L 1Z7, Canada
═══════════════════════════════════════════════════════

FOLDER STRUCTURE:
  index.html          ← Main website file (open this)
  logo.jpg            ← Your store logo
  products.csv        ← Product catalog (EDIT THIS to manage products)
  images/             ← Place product photos here
  README.txt          ← This file

HOW TO MANAGE PRODUCTS (products.csv):
  Open products.csv in Excel, Google Sheets, or any editor.
  
  COLUMNS:
  - id          : Unique number for each product (don't repeat)
  - name        : Product name shown on website
  - category    : puja / temple / incense / idols / gifts / accessories
  - catLabel    : Display label (e.g. "Puja Samagri")
  - price       : Selling price in CAD (numbers only)
  - oldPrice    : Original price (leave blank if no discount)
  - badge       : bestseller / new / sale (or leave blank)
  - rating      : e.g. 4.8
  - reviews     : Number of reviews (integer)
  - availability: YES = visible on site, NO = hidden
  - imageName   : Photo filename in the images/ folder (e.g. brass-diya.jpg)
  - description : Short product description

HOW TO ADD PRODUCT IMAGES:
  1. Take/download a photo of your product
  2. Name it something simple (e.g. puja-thali.jpg)
  3. Place it in the images/ folder
  4. Put that filename in the imageName column in products.csv

HOW TO VIEW THE WEBSITE:
  - Double-click index.html to open in a browser
  - For products.csv to load properly, use a local web server OR
    upload all files to your web hosting as-is

UPLOADING TO WEB HOSTING:
  Upload ALL files and the images/ folder together, keeping
  the same folder structure. The website will work instantly.

SUPPORT:
  The website auto-loads products.csv on startup.
  If csv is missing, it uses 8 built-in demo products.
  You can also click "Reload Products File" at the bottom
  of the website to manually load a CSV or Excel file.

═══════════════════════════════════════════════════════
