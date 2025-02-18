# Web Scrapping 

Technology used: *python, beautiful soup, pandas*

Amidst planning a vacation to Berlin for my family, I figured I could use my analytics knowledge to help organise all the restaurant information in that area.  
I decided to use **Beautiful Soup** to try to extract data and create a dataset with all the restaurants in Berlin.

## Python file

The whole web scrapping process was performed using Beautiful Soup library [*collecting_data.py*](https://github.com/akshitagadiparthi/web_scrapping_project/blob/main/collecting_data.py).

The process is also included in the jupyter notebook file [*web_scrapping_restaurants_in_berlin.ipynb*](https://github.com/akshitagadiparthi/web_scrapping_project/blob/main/web_scrapping_restaurants_in_berlin.ipynb).

## Output

Output file in form dataset as .csv file [*dataset_berlin_restaurants.csv*](https://github.com/akshitagadiparthi/web_scrapping_project/blob/main/dataset_berlin_restaurants.csv).

The new created dataset was used to further analysis. 

## Visualisation

The gathered data was used to create an [*interactive map of restaurants in Berlin*](https://public.tableau.com/app/profile/akshita.gadiparthi2602/viz/RestaurantsinBerlin_17396414876560/RestaurantsinBerlin?publish=yes) in Tableau Public.

# **Web Scraping & Data Visualization - Berlin Restaurants**

## **Overview**
While planning a vacation to Berlin, I leveraged my analytics expertise to organize restaurant information efficiently. Using web scraping techniques, I compiled a dataset containing details of restaurants in Berlin and visualized the insights in an interactive dashboard.

## **Technology Used**
- **Python**: Data extraction and processing
- **BeautifulSoup**: Web scraping
- **Pandas**: Data cleaning and structuring
- **Tableau Public**: Data visualization

## **Web Scraping Process**
The entire web scraping operation was conducted using **BeautifulSoup** and stored in `collecting_data.py`.

Additionally, a Jupyter Notebook (`web_scrapping_restaurants_in_berlin.ipynb`) documents the process with detailed explanations and code snippets.

## **Output**
- A structured dataset in **CSV format** (`dataset_berlin_restaurants.csv`) containing Berlin restaurant details.
- The dataset was further utilized for **data analysis and visualization**.

## **Interactive Dashboard**
The gathered data was processed and visualized to create an **interactive restaurant map** using **Tableau Public**.

### **How to Recreate This Project**
#### **1. Install Dependencies**
```bash
pip install beautifulsoup4 pandas
```

#### **2. Run Web Scraping Script**
```bash
python collecting_data.py
```

#### **3. Load Dataset for Analysis**
Use Jupyter Notebook to analyze and clean the data.
```bash
jupyter notebook web_scrapping_restaurants_in_berlin.ipynb
```

#### **4. Visualize in Tableau**
- Load the cleaned dataset into **Tableau Public**.
- Create an **interactive map** showcasing Berlin restaurants.
- Publish and share insights.

---

## **Use Cases & Benefits**
- **Tourists & Travelers**: Find top-rated restaurants based on real data.
- **Data Analysts**: Practice web scraping, data wrangling, and visualization.
- **Restaurant Owners**: Understand competition and customer preferences.

---

