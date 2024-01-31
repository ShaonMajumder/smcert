# SmCert - Secure Certificates for Your Project

SmCert is a script that simplifies the process of generating and installing local Certificates and Certificate Authorities (CAs) for your project.

## Prerequisites

Linux

## Getting Started

1. Clone the Repository:

```bash
git clone https://github.com/ShaonMajumder/smcert.git
cd smcert
```

2. Run the Script:

```bash
./smcert.sh
```

3. Follow the On-Screen Prompts:

- Enter the project certificates path.
- Sit back and let SmCert do its magic!

## Notes

- SmCert will ask you for the project certificates path where it will generate and install the necessary certificates and CA files.

- Ensure that Apache2 is installed on your system before running SmCert.

- The script will restart the Apache2 server after generating the certificates.

## Author

Shaon Majumder
smazoomder@gmail.com
