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
jupyter notebook project2-checkpoint.ipynb
```
## Business insights
Most frequently prescribed medicines
<img width="1079" height="667" alt="image" src="https://github.com/user-attachments/assets/2a64193c-1ba7-40a5-a700-2acd31b7d531" />

Doctor wise Prescription Volume
<img width="1074" height="641" alt="image" src="https://github.com/user-attachments/assets/eec74927-d6f1-4e80-95ac-11d64bc19816" />


Gender wise Prescription Distribution
<img width="674" height="488" alt="image" src="https://github.com/user-attachments/assets/814ed227-12a4-463d-8be0-8945b8547891" />


Age Group vs Number of Prescriptions
<img width="673" height="482" alt="image" src="https://github.com/user-attachments/assets/d5bb5b76-c555-49f1-995d-6ccccc1761f8" />


Doctors with High Prescription Volume
<img width="862" height="580" alt="image" src="https://github.com/user-attachments/assets/b3d20350-42e9-4c48-923c-0599959fbf05" />


Daily Prescription Trend
<img width="1051" height="644" alt="image" src="https://github.com/user-attachments/assets/a97d77fb-2f1a-41f5-8620-84870af3a59c" />


Data Quality Comparison
<img width="588" height="481" alt="image" src="https://github.com/user-attachments/assets/9fff9dd2-e731-469f-87c5-8d0ee36bf24a" />











