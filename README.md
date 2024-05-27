# Passive Information Gathering Tool (passive)

`passive` is a command-line utility designed for passive information gathering. It allows users to query public data sources to find information linked to a full name, IP address, or username across various platforms. This tool is intended for ethical use only, such as in penetration testing, security assessments, or research.


## Version
1.0.0

## Features

- **Full Name Search**: Look up addresses and phone numbers associated with a full name.
- **IP Address Lookup**: Retrieve location and provider information for a given IP address.
- **Username Search**: Check for the existence of a username on platforms like Facebook, Instagram, Reddit, GitHub, Twitch, and YouTube.

## Installation

To use `passive`, you need Python 3 and the following Python packages:
- `requests`
- `bs4` (BeautifulSoup4)

You can install the required packages using pip:

```bash
pip install requests bs4
```

## Usage
```bash
./passive.py [OPTIONS]
```

### Options
- `-fn, --fullname`: Perform a full name search.
- `-ip, --ipaddress`: Perform an IP address lookup.
- `-u, --username`: Perform a username search.

### Examples
```bash
./passive.py -fn "John Doe"
./passive.py -ip
./passive.py -u "johndoe"
```

## Help
For more information on how to use `passive`, run the following command:

```bash
./passive.py --help
```

## Contributing
Contributions to passive are welcome.  
Please feel free to submit pull requests or create issues for bugs and feature requests.

## Disclaimer
This tool is provided for educational and ethical testing purposes only.  
The authors are not responsible for misuse or damage caused by this tool.