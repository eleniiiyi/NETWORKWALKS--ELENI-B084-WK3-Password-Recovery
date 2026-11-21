# Week 3: Password Recovery Lab

A learning journal for my third week as a cybersecurity intern with NetworkWalks. This repository documents my first hands-on practice with password recovery on provided, password-protected PDF files.

## Learning objectives

- Understand that password recovery tools operate on hashes extracted from protected files.
- Practice extracting PDF hashes and working with them in a controlled lab.
- Observe how wordlists are used to test candidate passwords.
- Reflect on why strong, unique passwords matter.

## Lab activities

### 1. John the Ripper (JTR) with Johnny

- Extracted hashes from three provided PDF files.
- Loaded the hashes into Johnny, the graphical interface for John the Ripper.
- Ran password recovery attacks in the training environment.
- Recovered the passwords for all three provided files.

### 2. NetworkWalks password recovery tools

- Used the NetworkWalks Hash Calculator to extract a PDF hash.
- Submitted the hash to the Password Cracker tool.
- Observed the wordlist-based recovery process.

## Results

Screenshots is added to [`screenshots/`](screenshots/).

## Key takeaway

This exercise introduced me to practical password recovery and showed how weak passwords may be identified through wordlist-based guessing. It reinforced the value of using strong, unique passwords.

## Responsible use

These techniques were practiced for educational purposes on files and hashes provided for the internship exercise. Use password recovery tools only on files and systems you own or are explicitly authorized to assess. Do not publish recovered credentials, hashes, or confidential course materials.
