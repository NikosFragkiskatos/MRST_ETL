# MRTS Dataset ETL Project

This project is an ETL (Extract, Transform, Load) pipeline designed to work with the MRTS dataset. It demonstrates efficient data manipulation and storage techniques using Python. The project covers the extraction of data, its transformation into a more useful format, and the loading of the transformed data into a MySQL database for further analysis. This is my submission I had done for the MIT Data Engineering program.

## Installation

### Prerequisites
- Python 3.x
- MySQL Server
- Jupyter Notebook or JupyterLab
  
### MySQL Setup
Before running the ETL scripts, ensure you have MySQL Server installed and that it is running on localhost at the default port 3306. You will need to create a database for the project and provide your own credentials. The ETL script will require you to update the `db.yaml` file with your MySQL username, password, and database name.

## Setup

### 1. Clone the repository using the following command:
`git clone https://github.com/NikosFragkiskatos/MRST_ETL.git`

### 2. Install the required Python libraries:
- In a Terminal or Command Prompt, run:
  `pip install pandas numpy PyYAML mysql-connector-python matplotlib`
  
## Usage

### 1. Start the Jupyter Notebook:
- Navigate to the project directory and run:
  `jupyter notebook ETL_MRST_Notebook.ipynb`


### 2. Execute the notebook cells:
- Follow the instructions within the notebook to extract, transform, and load the dataset.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open-sourced under the MIT License - see the `LICENSE.txt` file for details.
