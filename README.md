# CDN Cloud front
![Screenshot_20240427-152508_Termux](https://github.com/MrPYTHONI/websocket_cloudflare_cloudfront_Scan/assets/155364237/c5fdc5c1-203f-415e-8ce1-125631d98ad9)

# CDN Cloud flaer 
![Screenshot_20240427-152619_Termux](https://github.com/MrPYTHONI/websocket_cloudflare_cloudfront_Scan/assets/155364237/cc39324b-5bf1-4a66-b441-ac723d1924e3)


---

CloudScanX - Full Installation and Usage Guide

What is CloudScanX?

CloudScanX is a tool designed for scanning and identifying cloud infrastructure vulnerabilities, primarily focusing on detecting cloud services like Cloudflare, Fastly, Google Frontend, and other cloud providers. The tool can scan IP ranges and perform checks for these services to identify potential security risks.


---

1. Installation Guide

On Termux (Android)

1. Update Termux and Install Required Packages:

First, update your Termux environment and install the necessary packages:


pkg update && pkg upgrade
pkg install python git


2. Clone the Repository:

Clone the CloudScanX repository from GitHub:


git clone https://github.com/MrPYTHONI/CloudScanX.git
cd CloudScanX


3. Install Python Dependencies:

Install the required Python dependencies using pip:


pip install -r requirements.txt


4. Run the Tool:

You can now run the tool by using the following command:


python CloudScanX.py




---

On Kali Linux

1. Update Kali and Install Dependencies:

Ensure your Kali Linux system is up to date and install the required dependencies:


sudo apt update && sudo apt upgrade
sudo apt install python3 git


2. Clone the Repository:

Clone the CloudScanX repository from GitHub:


git clone https://github.com/MrPYTHONI/CloudScanX.git
cd CloudScanX


3. Install Python Dependencies:

Install the necessary Python dependencies using pip:


pip3 install -r requirements.txt


4. Run the Tool:

Run the tool with:


python3 CloudScanX.py




---

On Windows

1. Install Python:

Download and install Python from the official website: Python.org. Ensure that you check the option to add Python to your system PATH during installation.



2. Install Git:

Download and install Git from Git-SCM.



3. Clone the Repository:

Open Command Prompt or PowerShell, then clone the repository:


git clone https://github.com/MrPYTHONI/CloudScanX.git
cd CloudScanX


4. Install Python Dependencies:

Install the required dependencies using pip:


pip install -r requirements.txt


5. Run the Tool:

To run the tool, use the following command:


python CloudScanX.py




---

2. Usage Instructions

Once the tool is installed, you can use it to scan IP ranges and detect cloud services. The basic usage format is:

python CloudScanX.py <IP Range or File> -t <Threads> -p <Port> -P <Proxy> -o <Output File>

Where:

IP Range or File: The IP range (e.g., 192.168.1.0/24) or a file containing a list of IP addresses to scan.

-t <Threads>: The number of threads to use for the scan (default is 10).

-p <Port>: The port to scan (default is port 80).

-P <Proxy>: Optional. Use a proxy server in ip:port format (e.g., 192.168.1.100:8080).

-o <Output File>: Optional. Save the results to a specified output file.



---

Example Usage

Example 1: Scan an IP Range with Default Settings

python CloudScanX.py 192.168.1.0/24

This will scan the entire range of IPs from 192.168.1.0 to 192.168.1.255 using the default port (80) and 10 threads.

Example 2: Scan with Custom Settings

python CloudScanX.py 192.168.1.0/24 -t 20 -p 443 -o results.txt

This will scan the IP range 192.168.1.0/24 with 20 threads, targeting port 443, and save the results to results.txt.


---

3. CloudScanX Features and Functionality

CloudScanX is designed to detect cloud infrastructure vulnerabilities by checking for the presence of specific cloud providers like:

Cloudflare

Fastly

Google Frontend

Other Cloud Providers


The tool works by scanning the provided IP range and checking if the target IPs belong to any of the supported cloud services. If a cloud service is detected, the tool will flag it, helping users identify potentially vulnerable cloud infrastructure.


---

4. Conclusion

With CloudScanX, you can easily identify cloud infrastructure services in your target network. By following the installation and usage instructions, you’ll be able to run the tool on Termux, Kali Linux, or Windows.

If you encounter any issues, refer to the README.md file for additional troubleshooting tips or check the GitHub repository for updates.

# 𝐌r𝐏𝐘𝐓𝐇𝐎𝐍🏴‍☠️
![Screenshot_20231105-191851_Video Player](https://github.com/MrPYTHONI/websocket_cloudflare_cloudfront_Scan/assets/155364237/84c0bab7-1ee4-4f35-a48a-846d77a5d57d)

. ♟Telegram♟ 

https://t.me/PYT_HON3

➖➖➖➖➖➖➖➖➖➖

♟You Tube♟

https://www.youtube.com/@Mr_PYTHON3

👇👇

https://youtu.be/b90hGxWwoCg?si=eWTqK1ZajOuPy3vH

➖➖➖➖➖➖➖➖➖➖
♟TIK TOK♟ 

tiktok.com/@mr_python_fpi
