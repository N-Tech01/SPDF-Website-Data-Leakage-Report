# SPDF Website Data Leakage Report

## Overview
Hello,  
My name is Navarath, and I would like to bring a potential security issue to your attention. I discovered this issue while exploring websites using Google Dorks as part of my learning in basic ethical hacking at CADD Centre. I am currently studying in 8th standard.

## Description of the Issue
While searching through Google using dorks, I came across sensitive data accessible on the **NASA's SPDF (Space Physics Data Facility)** website. Specifically, I noticed that some private data is exposed through the following link:  
`https://spdf.gsfc.nasa.gov/pub/`

This directory may contain sensitive files that could be accessed by unauthorized users.

> **Disclaimer**: This project is for educational purposes only.  
> **Note**: The link is functional and accessible.

### Sensitive Information Found:
In the directory, I opened the file **"000_readme.txt"** and then, I found the following sensitive information related to NASA's SPDF:

#### Contact Information:
- **Robert M. Candey** (Head of SPDF)
- **Tamara J. Kovalick** (Technical Contact)
- NASA email addresses:
  - `Robert.M.Candey@nasa.gov`
  - `tamara.j.kovalick@nasa.gov`
  - `gsfc-spdf-support@lists.nasa.gov`

#### FTP and FTPS Access Details:
- FTP and FTPS URLs for accessing data:
  - `ftp://spdf.gsfc.nasa.gov`
  - `https://spdf.gsfc.nasa.gov`
  - `ftp://cdaweb.gsfc.nasa.gov`
  - `https://cdaweb.gsfc.nasa.gov`
- FTPS Readme URL: `https://spdf.sci.gsfc.nasa.gov/ftps_readme.html`

#### Metadata and Data Descriptions:
- Details on data directories, metadata files, and the use of master CDFs for data description and organization.

#### Data Access Instructions:
- Information on accessing data through CDAWeb, including the use of CDF software and web services.

This information appears to be sensitive, and I have reported it for review still i didn't get any response from the authorities.

## Steps
1. Use Google Dorks to search for sensitive directories and files exposed to the public.
2. Visit the directory link: `https://spdf.gsfc.nasa.gov/pub/`.
3. Open the **"000_readme.txt"** file to view the sensitive data.

> **Disclaimer**: Use this for educational purposes only.

## Recommendation
Please review this report and ensure the security of your website. Kindly take necessary actions to secure sensitive areas and implement proper access controls to prevent unauthorized access to private data.

## Disclaimer
This project is posted here for ethical purposes only. Any misuse of this report for illegal activities or malicious purposes is strictly prohibited and I am not responsible for any consequences arising from such actions. All content in this repository is protected under copyright law. Unauthorized republishing without proper paper is prohibited.

## Request for Acknowledgment
I hope this report is helpful.

Thank you.  

By Navarath H.S.
