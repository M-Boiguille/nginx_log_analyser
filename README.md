# Nginx Log Analyser

Project from: [https://roadmap.sh/projects/nginx-log-analyser](https://roadmap.sh/projects/nginx-log-analyser)

Nginx Log Analyser is a Bash script designed to extract and display key insights from an Nginx access log file. It simplifies log analysis by identifying top IP addresses, requested paths, and response status codes.

## Features
- Identifies the top 5 IP addresses making requests.
- Extracts the top 5 most requested paths.
- Displays the top 5 HTTP response status codes.

## Usage
### Syntax
```
./nginx-log-analyser
```
- **Input:** The script expects the Nginx access log file to be named `nginx-access.log` and located in the current working directory.

### Output
1. **Top 5 IP addresses:** Displays the IPs with the most requests.
2. **Top 5 requested paths:** Lists the most accessed paths.
3. **Top 5 response status codes:** Provides the most common HTTP response codes.

### Example
Run the script directly in the directory containing the `nginx-access.log` file:
```bash
./nginx-log-analyser
```

### Requirements
- **Tools used:**
  - `sort`
  - `uniq`
  - `awk`
  - `perl`
  - `sed`
  - `head`

## Development Environment
- **OS:** Linux (Ubuntu)
- **Language:** Bash
- **Dependencies:** Standard Unix tools

## Improvements
- Allow user input to specify the log file name and location.
- Align output text dynamically for better readability.
- Support for additional log formats.
- Export the analysis results to a file.

## Conclusion
This project provides a simple yet effective tool for analysing Nginx access logs. It helps system administrators quickly identify key trends and issues from logs with minimal effort.

The [project link](https://roadmap.sh/projects/nginx-log-analyser).

Thanks to [https://roadmap.sh](https://roadmap.sh/).