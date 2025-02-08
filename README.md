 EXAM 3.0 - README

EXAM 3.0 - Secure Exam Management System
========================================

**EXAM 3.0** is a decentralized, secure, and transparent platform for managing exams. The system ensures exam papers are securely stored on IPFS using the Pinata cloud service and deployed on a private blockchain (using Hardhat). The system automates exam paper access at scheduled times in exam centers using a client application, and candidates can register through the website.

Table of Contents
-----------------

1.  [Project Overview](#project-overview)
2.  [Tech Stack](#tech-stack)
3.  [Features](#features)
4.  [Installation](#installation)
5.  [Smart Contract Deployment](#smart-contract-deployment)
6.  [Frontend Setup](#frontend-setup)
7.  [IPFS and Pinata Integration](#ipfs-and-pinata-integration)
8.  [Database and WordPress Integration](#database-and-wordpress-integration)
9.  [Screenshots](#screenshots)
10.  [Contributing](#contributing)
11.  [License](#license)

Project Overview
----------------

**EXAM 3.0** aims to provide an end-to-end secure exam system:

*   Exam papers are uploaded by the admin and stored in IPFS.
*   Papers are revealed only at the scheduled exam time.
*   The system supports user registration through the website (built with React and Next.js) .
*   Exam details, such as the time, center, and other information, are stored in MySQL and accessible via a user portal.
