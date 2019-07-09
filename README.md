# Details

- Manage password policy for backend users.
- Manage password policy for front-end users (RainLab.Users).
- Add custom validation rules (can be used in other plugins too):
  - Check your hashed password in haveibeenpwned.com database https://haveibeenpwned.com/API/v2#SearchingPwnedPasswordsByRange
  - Minimum upper case (min_upper_case:value)
  - Minimum lower case (min_lower_case:value) 
  - Minimum number (min_number:value)
  - Minimum special characters (min_special_char:value)


# Installation

- Install Acte.PasswordPolicy plugin in plugins/acte/passwordpolicy.
- Go to PasswordPolicy settings to configure policies.

# To do

- Password expiration to force password change every X time.
- Select level of pwned time password has been seen.
- Any suggestions are welcome.
