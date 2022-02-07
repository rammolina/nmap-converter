# nmap-converter
Python script for converting nmap reports into XLSX. This version adds a tab with the regular results of the portscan and keeps in a different tabs the parsed output of the NSE scripts.

# Requirements
```bash 
sudo pip3 install python-libnmap
sudo pip3 install XlsxWriter
```
or 
```bash 
sudo pip3 install -r requirements.txt
```
# Usage
```bash
usage: python3 nmap-converter.py [-h] [-o XLSX] XML [XML ...]

positional arguments:
  XML                   path to nmap xml report

optional arguments:
  -h, --help            show this help message and exit
  -o XLSX, --output XLSX  path to xlsx output
```
# Acknowledgments
- Forked and improved over:[@mrschyte](https://github.com/mrschyte/) version [https://github.com/mrschyte/nmap-converter](https://github.com/mrschyte/nmap-converter)