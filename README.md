![portada](https://github.com/ssanchezromer/supers/assets/122234525/733c8c9a-ae1b-4a96-8dc3-00fc427a6b49)

# Data Typology and Lifecycle – UOC
## Web Scraping Practice 1 – Supermarket Price Comparison

This project is part of the course "Data Typology and Lifecycle" from the Master’s in Data Science at UOC.
We have developed a web scraper that extracts product prices from major supermarkets in Spain and compares them. Finally, the results are saved in a CSV file, and we created a Flask app to visualize them.

## Context
In this activity, data was collected to compare product prices from three different supermarkets: Mercadona, Caprabo, and Bonpreu.

Websites (links):
<ul>
<li><strong>Mercadona:</strong>&nbsp;&nbsp;<a href="https://tienda.mercadona.es/" target="_blank">https://tienda.mercadona.es/</a></li>
<li><strong>Caprabo:</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://www.capraboacasa.com/es" target="_blank">https://www.capraboacasa.com/es</a></li>
<li><strong>Bonpreu:</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://www.compraonline.bonpreuesclat.cat/products" target="_blank">https://www.compraonline.bonpreuesclat.cat/products</a></li>
</ul>

This initiative was developed in response to the significant increase in prices of various products, such as olive oil—an issue that has affected consumers’ budgets and led to a growing interest in identifying the most affordable shopping options.

## Team members:

Sergi Sánchez Romero

Lucia Blanc Velázquez


## Repository content:

- **Readme.md:** Brief summary of the project contents.
- **source/.:** Folder containing the main program code (main.py) and the Flask application code (run.py). It also includes:
  - **app/.:** Folder with the code to initialize the Flask app.
  - **csv/.:** Folder containing the resulting dataset (products.csv). Each supermarket folder also contains the corresponding CSV file for the scraped data from that site.
  - **modules/.:**: Folder with the required custom modules.
  - **requirements.txt:** File listing the libraries needed for the project environment.
- **pdf/comparacionPrecioSupers.pdf:** PDF document with the detailed explanation of the project.
- **video/.:** Project presentation video.
  



## DOI of the Generated Dataset
The dataset is titled **Comparison of products from Mercadona, Caprabo and Bonpreu** and is published on Zenodo.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10086087.svg)](https://doi.org/10.5281/zenodo.10086087)

## Steps to Create the Environment and Run the Scraper:

Once you have downloaded the code inside the **source** folder, follow these steps to run the application:

**1. Create a virtual environment:**

> python -m venv *env_name*

**2.  Activate the environment:**

  Windows:

> *env_name*\Scripts\activate

  MacOS & Linux:

> *env_name*/bin/activate

**3. Install the required libraries:**

> pip install -r requirements.txt

**4. Run the program**

> python main.py

![final_scraping](https://github.com/ssanchezromer/supers/assets/122234525/40c6681f-5853-467b-91d7-b98e0dbb9099)


![flask](https://github.com/ssanchezromer/supers/assets/122234525/63138454-be59-43ef-a938-3da1735e7176)

