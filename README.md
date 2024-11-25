# PhoneBook Vault

## Overview

**PhoneBook Vault** is a repository that contains all possible combinations and permutations of Kenyan phone numbers, organized by number prefixes (071 to 079). This resource is designed for pentesting, security research, and number enumeration tasks, providing a comprehensive dataset to test phone number-related security vulnerabilities or enumerate potential numbers within the Kenyan phone number range.

### Purpose

- **Penetration Testing**: Ideal for testing phone number-based authentication systems or security measures that rely on phone numbers.
- **Number Enumeration**: Useful for identifying and validating possible phone numbers within the specified Kenyan number ranges.

### Structure

The repository is organized into files based on the phone number prefixes for Kenyan phone numbers. Each file contains all permutations and combinations of phone numbers starting with a particular prefix, formatted as **071XXXXXXX**, **072XXXXXXX**, etc., up to **079XXXXXXX**.

### File Structure

- Each file is named according to the phone number prefix it contains:
    - `phonenumbers-071.txt` contains all numbers starting with `071`.
    - `phonenumbers-072.txt` contains all numbers starting with `072`.
    - ...
    - `phonenumbers-079.txt` contains all numbers starting with `079`.

- Each file consists of 10-digit phone numbers in the following format:
    - Example:
        - `0710000001`
        - `0710000002`
        - `0710000003`
        - ...
        - `0799999999`

### Example of a Phone Number in the File

Each number is listed as a 10-digit string with no spaces or separators:


### Usage

The PhoneBook Vault repository can be utilized for several purposes, including:

1. **Penetration Testing**: 
   - Test phone number validation systems, brute-force authentication systems, or any service that requires phone number input.
   - Automate attacks on systems that use phone numbers for registration, 2FA, or other security mechanisms.

2. **Number Enumeration**:
   - Enumerate possible numbers in the Kenyan telecom number space (071-079 prefixes).
   - Validate number availability or test systems for vulnerability to phone number-based attacks.

3. **Security Research**:
   - Use the data for security research related to telecommunication systems or enumeration vulnerabilities.

### How to Use

1. **Download or Clone the Repository**
   - You can either download the repository as a ZIP file or clone it using Git:
     ```bash
     git clone https://github.com/yourusername/PhoneBookVault.git
     ```

2. **Access the Files**
   - Each file in the repository is accessible for reading. The files are organized by the phone number prefixes (`071` to `079`), so you can easily navigate and open them based on your testing needs.

3. **Search for Numbers**
   - You can search for specific phone numbers in the text files using standard text search tools (e.g., `grep` on Linux/MacOS or `findstr` on Windows).

4. **Automated Scripts**
   - Use automated scripts to iterate through the files and perform bulk testing on the numbers, for example:
     ```python
     with open("phonenumbers-071.txt", "r") as file:
         for line in file:
             # Process each number in the file
             pass
     ```

### Disclaimer

This repository is **strictly for ethical and legal use only**. It is intended for use in penetration testing, security research, and educational purposes. Unauthorized use of this dataset for malicious activities, such as harassment or illegal enumeration, is prohibited and may be subject to legal consequences.

By using this repository, you agree to use it responsibly and in accordance with all applicable laws.

### Contributing

If you have suggestions for improvements or additions, feel free to submit an issue or a pull request. Contributions are welcome!

### License

This repository is released under the **MIT License**.

---

### Contact

For further information or inquiries, please contact:
- Email: [newerbandit@proton.me]
- [GitHub](https://github.com/njeru-codes)

---

### Acknowledgments
- **Crunch Tool**: This dataset was built using the powerful **[Crunch](https://github.com/Crunch/Crunch-2)** tool, which allows for the generation of all possible permutations and combinations of numbers within a given pattern. 

