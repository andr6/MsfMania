# AccessMe

## Python AV Evasion Tools

AccessMe is a command line tool, developed in Python, which aims to be able to generate executables (32/64 bits) containing a Metasploit or other payload. 
When generating the payload with Msfvenom, the output is incremented in a polymorphic code in C language. 
The main objective being antivirus evasion, this code contains random functions allowing it. 
It also contains evasion functions that the user can configure himself.

## Version 1.1.0.1
New features:
```
1- Restructured source code.
2- Bug correction.
```

## Requirements
```
1. Latest version of Kali Linux
2. The kali-rolling repository
3. Python3
```
## Usage
```
1. python3 setup.py (Execute only one times)
2. python3 AccessMe.py
```
## Features
