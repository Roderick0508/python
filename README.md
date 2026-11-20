# Sensor monitor - python assignment 1
## Roderick Bloemert ELV2 20/11/2026
this program generates and visualizes selected sensor input readings using numpy and matplotlib. 
The readings are saved to a CSV file and can be loaded
again later.

## **Getting started**
- Python 3.8 or higher
- The packages listed in `requirements.txt` (NumPy and Matplotlib)

## **Usage**
- 1 Select generate or load
- 2 select the desired sensor
- 3 select the amount of readings you want to recieve
- 4 select the minimal value for the sensor
- 5 select the maximal value for the sensor
- 6 select the threshold value 
- the reading will then be showed in a histogram and grid. The readings will also be availlable in a CSV file. 


## Installation

```bash
git clone <your-repository-url>
cd sensor-analysis
pip install -r requirements.txt
```

## Usage

Run the program with:

```bash
python sensor_monitor.py
```

## Error handling

The program shows an error message and asks again when:

- text is entered where a number is expected
- the number of readings is zero or negative
- the minimum is greater than or equal to the maximum
- the threshold is outside the minimum and maximum
- `readings.csv` is missing, empty or invalid when loading
- the CSV file cannot be saved

## Project structure

```text
sensor-analysis/
├── sensor_monitor.py
├── requirements.txt
├── README.md
└── readings.csv
```
























































