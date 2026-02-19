# Digital Prescription Record Analysis Dashboard

A data analysis project for analyzing digital prescription records with comprehensive visualization and database management capabilities.

## Project Overview

This project analyzes prescription data to identify trends, most frequently prescribed medicines, doctor prescription volumes, patient medication histories, and other healthcare analytics insights.

## Tech Stack

### Backend & Data Processing
- **Python 3** - Core programming language
- **Pandas** - Data manipulation, cleaning, and analysis
- **SQLAlchemy** - Object-relational mapping (ORM) for database abstraction

### Database
- **MySQL** - Relational database for storing prescription records
- **MySQL Connector** - Python library for MySQL connectivity

### Data Visualization
- **Matplotlib** - Statistical visualization and plotting

### Development & Analysis
- **Jupyter Notebook** - Interactive analysis and development environment
- **CSV** - Data import/export format

## Data Sources

The project includes the following CSV datasets:
- `patients_1000.csv` - Patient information
- `doctors_1000.csv` - Doctor information
- `medicines_1000.csv` - Medicine catalog
- `prescriptions_1000.csv` - Prescription records

## Features

- Most frequently prescribed medicines analysis
- Doctor-wise prescription volume tracking
- Patient medication history analysis
- Interactive data visualizations
- MySQL database integration

## Project Structure

```
Digital presciption-P1/

├── project2.ipynb              # Additional analysis notebook
├── patients_1000.csv           # Patient data
├── doctors_1000.csv            # Doctor data
├── medicines_1000.csv          # Medicine data
├── prescriptions_1000.csv      # Prescription data
├── Digital Prescription Record Analysis DDL.txt  # Database schema
└── README.md                   # This file
```

## Requirements

See `requirements.txt` for Python dependencies. Key libraries include:
- pandas
- matplotlib
- sqlalchemy
- mysql-connector-python

## Database Setup

The project uses a MySQL database named `Digital_prescription_db`. Configure your database connection in the application code:

```python
engine = create_engine("mysql+mysqlconnector://user:password@localhost/Digital_prescription_db")
```

## Usage

### Jupyter Notebooks
Run analysis notebooks for data exploration and insights:
```bash
jupyter notebook project.ipynb
```


