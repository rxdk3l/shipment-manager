# Shipment Management System

A Python desktop application for managing wholesale/retail shipments with database tracking.

## Team Members
- **Person 1** (Raid Kellil): Database & Core Infrastructure
- **Person 2** (Houssem Eddine Maou): Shipments & Products UI
- **Person 3** (Rajad Beddiar): Farmers UI & Dialogs
- **Person 4** (Benbouzid Khireddine): Main Application & DevOps Configuration

## Features
- User authentication
- Shipment tracking
- Product inventory management
- Farmer/customer management
- SQLite database
- PyQt6 GUI

## Technologies Used
- **Python 3.11**: Programming language
- **PyQt6**: GUI framework
- **SQLite**: Database
- **Docker**: Containerization
- **GitHub Actions**: CI/CD Pipeline

## Project Structure
```
shipment-manager/
├── database.py          # Database operations (Person 1)
├── ui_widgets_1.py      # Shipments/Products UI (Person 2)
├── ui_widgets_2.py      # Farmers UI (Person 3)
├── main.py              # Application entry point (Person 4)
├── requirements.txt     # Python dependencies (Person 4)
├── Dockerfile           # Container configuration (Person 4)
├── .github/workflows/ci.yml  # CI/CD pipeline (Person 4)
└── README.md            # This file
```

## Running with Docker

### Build the container:
```bash
docker build -t shipment-manager .
```

### Run the container:
```bash
docker run -it shipment-manager
```

## Running Locally

### Install dependencies:
```bash
pip install -r requirements.txt
```

### Run the application:
```bash
python main.py
```

### Default login:
- **Username**: admin
- **Password**: password123

## CI/CD Pipeline
The GitHub Actions workflow automatically:
1. Tests Python syntax on every push
2. Builds the Docker container
3. Verifies the build succeeded

## DevOps Practices Demonstrated
- ✅ **Version Control**: Git & GitHub
- ✅ **Containerization**: Docker
- ✅ **CI/CD**: GitHub Actions
- ✅ **Automated Testing**: Syntax checking
- ✅ **Collaboration**: Multiple contributors
- ✅ **Documentation**: This README

## How We Collaborated
1. Split the application into 4 modules
2. Each team member worked on their assigned file
3. Used Git for version control
4. Implemented CI/CD pipeline
5. Containerized the application with Docker

## License
Educational project for DevOps module
