Project structure

automated-network-scanner/
│
├── src/
│   ├── network_scanner.py    
│   ├── report_generator.py   
│   └── config.json           
│
├── reports/
│   └── example_report.html   
│
                 
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/cryptic333/automated-network-scanner/tree/main
cd automated-network-scanner
Install Dependencies:
Ensure you have Python 3.x installed. Then, install the required Python libraries:

bash
Copy code
pip install -r requirements.txt
Usage
Basic Scan:
Run a basic network scan on a specified IP range:

bash
Copy code
python src/network_scanner.py --range 192.168.1.0/24
The scan results will be saved as an HTML report in the reports/ directory.

Custom Configurations:
Edit the config.json file to customize the scan settings (e.g., specify ports, add email notifications, etc.).

Configuration
Network Range: Specify the IP range to scan using the --range argument.
Alert Settings: Configure email alerts by adding your SMTP server details in the config.json file.
Output Location: Change the directory where reports are saved by modifying the output_dir field in config.json.
Example Output



