# Automated bKash/Nagad Payment Cross-checker (Google Forms)

Use Case: When the Transections ID (TxID) are collected via Google Forms. This script can be used to automatically cross-check the TxIDs with the TxIDs received as SMS in bKash/Nagad accounts.

<br>




## Requirement: 
- Android App: [SMS, Call - XML, PDF, CSV(Super Backup & Restore)](https://play.google.com/store/apps/details?id=com.greenchills.superbackup&hl=en&gl=US)
- Working knowledge of Python, Pandas



<br>


# How it Works
We make a CSV file containting all the SMS from our phone. We make a loop that takes the TxIDs collected from the Google Forms and see if any word match with the TxID. If yes, the entry is added to the Match Table, otherwise it is added to the Mismatch table. Super simple, eh?




<br>


## **Step 1: Your Google Form that looks something like this, with an input field for bKash/Nagad Transaction ID field. Download the Google forms responses file as Excel format.**

<a href="https://imgur.com/IgXSxPY"><img src="https://i.imgur.com/IgXSxPY.png" heigth="600" width="400" /></a> <a href="https://imgur.com/sUbAava"><img src="https://i.imgur.com/sUbAava.png" heigth="600" width="400" /></a>



<br>





## **Step 2: Convert all your SMS to CSV using the Super Backup (In the Bottom)**

<a href="https://imgur.com/P02IVzP"><img src="https://i.imgur.com/P02IVzP.jpg" heigth="400" width="200" /></a>
<br>

<br>

## **Step 3: Open The Python file in Jupyter Notebook/Lab and Input proper file names**

<a href="https://imgur.com/1YVgaKr"><img src="https://i.imgur.com/1YVgaKr.png" title="source: imgur.com" /></a>



<br>


## **Step 4: See Output! Check the "Match Table" and "Mismatch Table" (Only Mismatch Table Shown Here)**

<a href="https://imgur.com/QJ6hzWp"><img src="https://i.imgur.com/QJ6hzWp.png" title="source: imgur.com" /></a>
