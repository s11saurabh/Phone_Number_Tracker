# Phone Number Tracker

**Phone Number Tracker** is a Python-based tool that allows users to track and retrieve the location, carrier, and other geographical details of a given phone number. It leverages external APIs to gather accurate data and provides a simple interface for tracking phone numbers efficiently.

## Features

- Track phone numbers by retrieving details such as:
  - Country
  - Carrier
  - Location (city/state)
  - Timezone
- Simple and easy-to-use interface.
- Accurate information using external APIs.

## Prerequisites

Before running the project, ensure you have the following requirements:

- Python 3.x installed
- `phonenumbers` library
- Internet access (for API data retrieval)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/S11saurabh/Phone_Number_Tracker.git

2.  Navigate to the project directory:

   ```bash
   cd Phone_Number_Tracker

 3.  Install the required dependencies:

   ```bash
pip install -r requirements.txt
or manually install the necessary library:

   ```bash
pip install phonenumbers
4. (Optional) For enhanced tracking features like timezone and carrier, you may need to set up an external API (like Google’s Geolocation API). Add the API key in the script if necessary.

Usage

#Example 
  ```bash
Enter a phone number (with country code): +11234567890
Country: United States
Location: California
Carrier: AT&T
Timezone: America/Los_Angeles
