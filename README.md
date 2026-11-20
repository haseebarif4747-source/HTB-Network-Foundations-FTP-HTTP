# HTB Network Enumeration: FTP & HTTP

## Project Overview

This repository documents my hands-on practical work from HTB Academy, focusing on network enumeration and the investigation of FTP and HTTP services.

The objective was to identify exposed services, understand FTP anonymous access, retrieve an IT information note, and analyze HTTP request filtering through User-Agent header manipulation.

## Objectives

- Identify open ports and running services using Nmap.
- Understand FTP service enumeration.
- Investigate anonymous FTP access.
- Retrieve and analyze a text file from an FTP server.
- Understand HTTP request headers.
- Examine User-Agent-based request filtering.

## Tools Used

- Nmap
- FTP Client
- cURL
- Linux / Pwnbox
- GitHub

## Practical Methodology

### 1. Network Enumeration

Performed a targeted Nmap scan to identify available services and their versions.

### 2. FTP Enumeration

Investigated the FTP service and analyzed anonymous authentication.

### 3. File Retrieval

Used FTP file retrieval functionality to obtain the IT information note.

### 4. HTTP Request Analysis

Analyzed HTTP request filtering and examined the role of the User-Agent header.

### 5. Response Inspection

Sent an HTTP request with the required User-Agent value and inspected the server response.

## Screenshots

Screenshots documenting the practical workflow are available in the `Screenshots/` directory.

## Key Learnings

- Network service enumeration
- Port and service identification
- FTP protocol fundamentals
- Anonymous FTP access
- FTP file retrieval
- HTTP request headers
- User-Agent manipulation
- Basic HTTP response analysis

## Disclaimer

This documentation is intended for educational purposes and reflects work performed in an authorized HTB Academy lab environment. All practical testing was conducted within the designated lab environment.

Platform: Hack The Box Academy  
Focus: Network Foundations | FTP | HTTP

