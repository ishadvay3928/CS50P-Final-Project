# Medical Diagnosis System  

## Description  
The **Medical Diagnosis System** is a Python program that diagnoses diseases based on symptoms and calculates a patient's age using their birthdate. The program reads data from a CSV file, processes the information, and writes the diagnosis results to another CSV file.  

## Features  
- Reads patient details from a CSV file.  
- Diagnoses diseases based on predefined symptom patterns.  
- Calculates a patient’s age from their birth year.  
- Exports the processed results to a new CSV file.  

## Project Structure  
```
📂 Medical Diagnosis System
│-- 📄 project.py                 # Main program file  
│-- 📄 patients.csv               # Input CSV file with patient data  
│-- 📄 after.csv                  # Output CSV file with diagnosis results   
│-- 📄 README.md                  # Project documentation  
```

## Requirements  
- Python 3.x  
- Required Libraries:  
  - `csv` (for handling CSV files)  
  - `sys` (for command-line arguments)  

## Installation  
1. Clone this repository:  
   ```sh
   git clone https://github.com/ishadvay3928/CS50P-Final-Project/tree/main
   ```  
2. Navigate to the project directory:  
   ```sh
   cd CS50P-Final-Project  
   ```  

## Usage  
1. Prepare an input CSV file (`patients.csv`) with the following format:  
   ```
   name,symptoms,birthdate  
   John Bell,headache,2001
   Alice Boot,cold,2007
   Bob Brown,cough,2003
   ```

2. Run the program:  
   ```sh
   python project.py patients.csv after.csv  
   ```  

3. The program will generate an output CSV file (`after.csv`) with the results:  
   ```
   name,disease,age  
   John Bell,Migraine,Age21
   Alice Boot,Flu,Age15
   Bob Brown,Flu,Age19
   ```  

## Error Handling  
- Displays an error if the correct number of command-line arguments is not provided.  
- Ensures input and output files are in CSV format.  
- Handles file-not-found errors gracefully.  

## Contributing  
If you'd like to contribute, feel free to fork the repository and submit a pull request.  

## License  
This project is licensed under the MIT License.  
