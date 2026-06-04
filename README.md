# klean
Convert Kaduu CSV exports to a friendly markdown file

## Usage

```bash
# Create an unordered list of logins organized by the associated passwords and websites in markdown
./klean -i ACCOUNT_9172d7f4-0196-4d46-83c9-096ecc083f73.csv > data.md

# Create a wordlist out of the export's passwords
./klean -p -i ACCOUNT_9172d7f4-0196-4d46-83c9-096ecc083f73.csv > passwords.txt

# Create a wordlist out of the export's logins
./klean -l -i ACCOUNT_9172d7f4-0196-4d46-83c9-096ecc083f73.csv > logins.txt
```
