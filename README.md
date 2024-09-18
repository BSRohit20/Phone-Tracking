
```markdown
# Simple Python Projects

This repository contains two simple Python scripts that demonstrate different functionalities:

1. **Phone Number Location & Time Zone Tracker** (`phone_number_info.py`): Extracts details such as time zone, location, and service provider from a given phone number.
2. **WiFi Profile Password Extractor** (`wifi_info.py`): Retrieves and displays the saved WiFi network profiles and their passwords from your system.

## Features
### 1. Phone Number Location & Time Zone Tracker
- Get the time zone, location, and service provider by entering a phone number with the country code.

### 2. WiFi Profile Password Extractor
- List all saved WiFi profiles and their passwords on the system.

## Requirements

- Python 3.x
- Modules: 
  - `phonenumbers` (for phone number tracking)
  - `subprocess` (built-in for WiFi extraction)

### Installing Required Dependencies:

Before running the project, ensure that `phonenumbers` is installed:

```bash
pip install phonenumbers
```

## Files in the Repository

1. **`phone_number_info.py`**:
   - Run this script to track the time zone, location, and service provider based on the phone number.
   - Example:

     ```bash
     python phone_number_info.py
     ```

   - When prompted, enter the phone number with the country code:

     ```
     Enter the phone number with country code: +14155552671
     ```

     Output:
     ```
     timezone : ('America/Los_Angeles',)
     location : California
     service provider : Verizon
     ```

2. **`wifi_info.py`**:
   - Run this script to display saved WiFi profiles and their passwords (only works on Windows).
   - Example:

     ```bash
     python wifi_info.py
     ```

   - The output will list all the WiFi profiles and show their passwords if available:

     ```
     WiFi-Network-1              |  Password123
     WiFi-Network-2              |  
     ```

