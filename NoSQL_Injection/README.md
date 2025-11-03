# NoSQL Injection Exploit (nosql_exploit.py)

This Python script is designed to automate the password length discovery and the password cracking process for NoSQL Injection vulnerabilities.

The primary purpose of this tool is to automatically solve the password length and password content challenges in the **TryHackMe NoSQL Injection laboratory**. It identifies a successful match by checking for a redirect to the `sekr3tPl4ce.php` page.

This script was generated with the assistance of **Gemini 2.5 Pro**.

## Usage

The script requires four command-line arguments: `-url`, `-user`, `-session`, and `-maxlength`.


### Command Line Execution

Use the following format, replacing the placeholder values with your lab details:

```bash
python3 nosql_exploit.py -url "http://<TARGET_IP_ADDRESS>/login.php" -user "<USER_NAME>" -session "<COOKIE_VALUE>" -maxlength 15

[!NoSQL Exploit Success Screenshot](nosql_injection.PNG)
