linkEXFS
Description

linkEXFS is a Python script for extracting information from a given website. It can extract links, find parameters, enumerate directories and perform subdomain enumeration.
Requirements

    Python 3.x
    requests
    beautifulsoup4
    termcolor

Installation

    Clone this repository: git clone https://github.com/your_username/linkEXFS.git
    Install the required libraries: pip install -r requirements.txt

Usage

python linkEXFS.py

Options

When you run the script, you will be prompted to enter the website URL and select an action:

    Extract links
    Find parameters
    Enumerate directories
    Enumerate subdomains

Enter the corresponding number to select an action.
Examples

To extract links from a website:

less

python linkEXFS.py
[*] Enter the website URL: https://example.com
[*] What do you want to do?
[1] Extract links
[2] Find parameters
[3] Enumerate directories
[4] Enumerate subdomains
=> 1
[*] Extracting links...

https://example.com/
https://example.com/about
https://example.com/contact
...

To enumerate subdomains:

less

python linkEXFS.py
[*] Enter the website URL: https://example.com
[*] What do you want to do?
[1] Extract links
[2] Find parameters
[3] Enumerate directories
[4] Enumerate subdomains
=> 4
[*] Performing subdomain enumeration...
[!] input your domain : example.com

subdomain1.example.com
subdomain2.example.com
subdomain3.example.com
...

License

This project is licensed under the MIT License - see the LICENSE file for details.
