<h1>Scanning With NESSUS</h1>

<h2>**NESSUS Installation and Usage Guide**</h2>

This repository provides a comprehensive guide to installing, configuring, and using **Nessus**, a powerful vulnerability scanning tool. Nessus is widely used in cybersecurity for identifying vulnerabilities in systems, networks, and applications. This project includes step-by-step instructions for setting up Nessus on Linux and demonstrates how to run vulnerability scans, interpret results, and generate reports. 

Whether you're a beginner or an experienced security professional, this repository will help you harness the full potential of Nessus to enhance your security testing and vulnerability management workflows.

### Features:
- Detailed installation instructions for multiple platforms
- Configuration tips for optimal Nessus performance
- Instructions for launching and configuring vulnerability scans
- Guidance on analysing and interpreting scan results
- Best practices for scheduling and automating scans
- Troubleshooting tips for common issues

### Prerequisites:
- A valid Nessus license (Free or Professional)
- Basic knowledge of networking and cybersecurity

<h2>Languages and Utilities Used</h2>

- <b>NESSUS</b> 
- <b>VirtualBox</b>

<h2>Environments Used </h2>

- <b>Linux</b>

<h2>Program walk-through:</h2>

Go to google and search for Nessus downloads  
Download to downloads folder.  
Go to terminal and type in the following to unpack and install. (-i = install)

![Picture1](https://github.com/user-attachments/assets/d35b39db-5b3a-4eb2-b4d8-0111a4fc99e1)

Nessus main page

![Screenshot 2025-02-20 at 19 04 37](https://github.com/user-attachments/assets/e719f6bf-4793-4fd0-84d4-80a0fb6390b6)

Click new scan

![Screenshot 2025-02-21 at 20 04 46](https://github.com/user-attachments/assets/7029309e-cf9f-40e3-8046-1589ff5d1889)

Click basic network scan

![Screenshot 2025-02-21 at 20 05 47](https://github.com/user-attachments/assets/abfd039d-5a1a-4042-bcd2-4a7b1fdfe75c)

Complete form

![Screenshot 2025-02-21 at 20 06 56](https://github.com/user-attachments/assets/dd8d8266-510c-4e73-88c2-e0ff754c096d)

in the discovery tab, change to all ports (like a -P)

![Screenshot 2025-02-21 at 20 08 45](https://github.com/user-attachments/assets/a9de4d6d-a8d2-4df5-89ba-d501fe17d077)

In assessment tab change from default to what is required depending on the task in hand.  
We selected known vulnerabilities as this will be much quicker than complex.

![Screenshot 2025-02-21 at 20 10 40](https://github.com/user-attachments/assets/ab5485fc-a9b6-4788-8c90-0968d64493b8)

Leave others as default, click save and launch

![Screenshot 2025-02-21 at 20 12 01](https://github.com/user-attachments/assets/cbd1dff3-9a1f-4ff3-abcb-7cc02ec6c870)

You can click in the scan to see how its going

![Screenshot 2025-02-21 at 20 12 54](https://github.com/user-attachments/assets/8e4940da-d51b-442d-a555-920ab6288326)

If you click the vulnerabilities tab you will see what has been found

![Screenshot 2025-02-21 at 20 13 53](https://github.com/user-attachments/assets/fbf298f7-cca1-448b-bb9e-803e9b82ead7)

Nessus automatically groups, click in settings and disable groups

![Screenshot 2025-02-21 at 20 15 43](https://github.com/user-attachments/assets/0e374ce9-83f8-4a50-9191-b78ec08f6a8f)

![Screenshot 2025-02-21 at 20 16 28](https://github.com/user-attachments/assets/bd2c9ab2-7616-4b20-9dcb-125006ea3829)

Click into the first critical

![Screenshot 2025-02-21 at 20 17 36](https://github.com/user-attachments/assets/bb3c7b25-d909-4fea-a68d-8c313070dcdb)

We would take a screen shot of this information and note this is out of date, noting what is running and what it should be patched too. <b> THIS IS INSUFFICIENT PATCHING </b>

![Screenshot 2025-02-21 at 20 19 37](https://github.com/user-attachments/assets/a59eb01e-8e75-4bc3-9297-b0c575416cca)

We would go through the others and depending on the severity we would write all these up.  
You can also download the Nessus file and there are programs to convert to excel, we would hand this over to the client and tell them we have covered some of the critical / high in the report but here are all the findings for you to review as this is a timed assessment so we focused on the lower hanging fruit and did what we could in the time allowed.

You need to prove all these things so just because the vulnerability scan says that we are running xyz, we need to confirm this and take a screen shot to show definitively that they are running this.


























<!--![Screenshot 2025-02-21 at 20 06 56](https://github.com/user-attachments/assets/3faf18f2-43d1-49f7-8c8f-e6153ec7c8db)







 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
