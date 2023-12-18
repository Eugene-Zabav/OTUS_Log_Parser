# Log File Analyzer

This script analyzes log files and provides information about the number of requests, request methods, IP addresses, and the longest requests.

## Usage

1. Make sure you have Python 3 installed.
2. Download and save the script in the desired directory.
3. Run the script, specifying the path to the log file or directory with log files as a command line argument:

```bash
python3 main.py /path/to/your/logfile.log
```

or

```bash
python3 main.py /path/to/your/directory
```

## Results
The script analyzes the log files and outputs the following information:

Total number of requests
Number of requests for each method
Top 3 IP addresses from which the most requests were made
Top 3 longest requests

The results are saved in a JSON file named with the current date and time, and are also printed to the console.
