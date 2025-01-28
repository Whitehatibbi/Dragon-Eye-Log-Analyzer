DragonEye Log Analyzer

DragonEye Log Analyzer is a lightweight and powerful Flask-based web application designed to analyze server log files for potential security threats. This tool helps identify brute-force attacks, SQL injection attempts, and other suspicious activities by parsing and analyzing server logs efficiently.


Features
Upload Log Files: Supports uploading server log files for detailed analysis.

Threat Detection:
Detects brute-force attacks based on IP activity patterns.
Identifies SQL injection attempts in log entries.

Report Generation:
Export analysis results in JSON, CSV, TXT, or view them directly on the browser.

Interactive Web Interface:
User-friendly UI with an intuitive file upload and report selection system.

How It Works
1-Upload your server log file using the web interface.
2-Choose the desired report format: JSON, CSV, TXT, or on-screen display.
3-View or download the results containing detected threats and logs.

Usage
Upload a log file (e.g., Apache or Nginx access logs) via the interface.
Select the report format and analyze the logs.
Investigate threats like brute-force IPs and SQL injection attempts using the generated report.


Technologies Used
Backend: Flask (Python)
Frontend: HTML
Threat Detection: Custom parsing logic for identifying brute-force attacks and SQL injection attempts.

Contribution
Contributions are welcome! Feel free to fork the repository and submit pull requests to improve the functionality or add new features.

License
This project is licensed under the MIT License.



