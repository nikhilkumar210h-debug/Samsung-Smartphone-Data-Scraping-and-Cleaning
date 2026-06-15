# Samsung Smartphone Data Scraping and Cleaning

> An end-to-end data collection project that scrapes Samsung smartphone information from the official Samsung website, cleans and transforms the raw data, and prepares an analysis-ready dataset using Python and Pandas.

## 📌 Project Overview

This project demonstrates the complete data acquisition workflow, from collecting data through web scraping to creating a structured and clean dataset suitable for data analysis and machine learning applications.

The notebook extracts smartphone details from Samsung's website, handles missing values and inconsistent formats, and exports the processed data as a CSV file.

## 🎯 Objectives

- Scrape Samsung smartphone data from the official Samsung website
- Convert unstructured web data into a structured dataset
- Clean and preprocess the collected data
- Handle missing values and data inconsistencies
- Prepare a high-quality dataset for analysis and visualization

## 📂 Dataset Features

The cleaned dataset contains the following features:

| Feature       | Description |
|---------------|-------------|
| `name`        | Smartphone model name |
| `price(inr)`  | Current selling price |
| `rating`      | Product rating |
| `reviews`     | Number of customer reviews |
| `color`       | Available color variant |
| `storage(GB)` | Storage capacity |

> **Note:** Available features may vary depending on product availability and website updates.

## 🗂️ Project Structure

```text
samsung-smartphone-data-scraping/
raw_samsung_data.csv cleaned_samsung_data.csv
samsung_scraping_and_cleaning.ipynb
README.md
requirements.txt
```

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Requests
- BeautifulSoup4
- Matplotlib

## 🔄 Workflow

1. Send HTTP requests to Samsung product pages.
2. Parse HTML content using BeautifulSoup.
3. Extract smartphone information.
4. Store the raw data in CSV format.
5. Clean and preprocess the dataset using Pandas.
6. Handle missing values and standardize data formats.
7. Export the final cleaned dataset.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/nikhilkumar210h-debug/Samsung-Smartphone-Data-Scraping-and-Cleaning.git
```

### 2. Navigate to the Project Directory

```bash
cd samsung_scraping_and_cleaning
```

### 3. Create a Virtual Environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS/Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells sequentially.

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
pandas
numpy
requests
beautifulsoup4
matplotlib
jupyter
```

Install all dependencies using:

```bash
pip install -r requirements.txt
```

## 📊 Output

The project generates:

- A raw dataset collected from the Samsung website
- A cleaned and structured CSV dataset ready for analysis

The cleaned dataset can be used for:

- Exploratory Data Analysis (EDA)
- Price comparison and trend analysis
- Data visualization
- Machine learning projects
- Market research

## ⚠️ Disclaimer

This project is intended for educational and research purposes only.

Please review and comply with Samsung's Terms of Service and `robots.txt` policies before scraping data from their website. The website structure may change over time, which could require updates to the scraping code.

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

To contribute:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a pull request

## 📄 License

This project is licensed under the MIT License.

## 👤 Author

**Nikhil Kumar**

GitHub: [@your-github-nikhilkumar210h-debug(https://github.com/nikhilkumar210h-debug)
