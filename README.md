# LogInsight  

LogInsight is a Python-based log file analyzer that extracts meaningful insights from server logs. It provides functionalities to analyze requests per IP address, identify frequently accessed endpoints, and detect suspicious activities. Additionally, the results are saved in a well-structured CSV file for further review.  

---

## Features  

- **Requests Per IP Address:** Analyze and display the count of requests made by each IP address.  
- **Most Accessed Endpoint:** Identify the most frequently accessed endpoint or resource in the log file.  
- **Suspicious Activity Detection:** Detect IP addresses with failed login attempts exceeding a customizable threshold.  
- **Save to CSV:** Export the analysis results to a structured CSV file with separate sections for each feature.  

---

## Usage  

1. Clone the repository:  
   ```bash
   git clone https://github.com/Priyansu-Bhandari/LogInsight-.git  
   cd LogInsight
   ```
2. Update the log_file_path variable in the script to point to your log file.
3. Run the script:
   ```bash
   python log_insight.py
   ```
4. View results in the terminal and the generated CSV file (log_analysis_results.csv).

---

## Example Output
1. Requests Per IP
```
IP Address           Request Count  
192.168.0.1          123  
203.0.113.45         98  
```
2. Most Accessed Endpoint
```
/endpoint/path (Accessed 345 times)  
```
3. Suspicious Activity
```
IP Address           Failed Login Attempts  
203.0.113.45         15  
192.168.0.1          12  
```

---

## CSV Output  

The results are saved in a file named `log_analysis_results.csv` with the following sections:  

- **Requests per IP**  
- **Most Accessed Endpoint**  
- **Suspicious Activity**  








