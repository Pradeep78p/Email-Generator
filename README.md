# Email-Generator Application
This is a simple Java console application that simulates an organization's internal **email account management system** for employees. It allows users to generate email addresses, set passwords, and update account settings interactively.

# Features
- Generate a default company email address using first and last name.
- Auto-generate a random password.
- Display employee account information.
- Update email address with a custom prefix.
- Change or reveal password using a verification code.
- Interactive menu-based system via the console.

# Usage Guidelines
- Input Valid Names
- Enter a valid first and last name when prompted.
- avoid using special characters or numbers for names to prevent email generation errors.
- Understanding Generated Email
- The generated email format is:
- firstname.lastname@company.com
- (e.g., john.doe@company.com)
- This is created automatically after entering your name.

Password Safety
- A random password is generated during account creation.
- You can view or change the password only by providing the correct verification code.
- Keep your verification code secure. It acts as your identity check.

Changing Email Address
- Use the menu option to update your email address.
- Only the prefix (before @gmail.com) is entered manually.
- The system automatically appends @gmail.com to maintain consistency.

Menu Navigation
- After entering the name, follow the menu options (1 to 5) to manage account settings.
- Avoid entering non-numeric input in menu choices (e.g., avoid typing one instead of 1).

Exit Safely
- Use option 5 to exit the program cleanly and close the scanner resource.
