🔐 Password Validator with OTP

A Python-based login authentication system featuring password 
validation, OTP-based password reset using Twilio, login attempt 
logging, and account security.

✨ Features

- 🔑 Username & password authentication
- 📱 OTP-based password reset using Twilio
- 🚫 Maximum login attempt limit
- 📝 Login activity logging
- 👤 Multiple user support
- ⚡ Simple command-line interface

🛠️ Technologies Used

- Python 3
- Twilio API
- Logging module
- Random module

📂 Project Structure

.
├── Login_sys_pass_reset_logged.py
├── password_attempts.log
└── README.md

🚀 Installation

1. Clone the repository:

git clone https://github.com/yourusername/password-validator-with-otp.git
cd password-validator-with-otp


2. Install dependencies:

pip install twilio


3. Configure your Twilio credentials using environment variables 
4. (recommended).

4. Run:

python Login_sys_pass_reset_logged.py


📸 Features Demonstrated

- Secure login validation
- OTP verification workflow
- Password reset
- Logging of successful and failed attempts

🔒 Security Note

For public repositories: - Do not commit API keys or tokens. - Store 
secrets in a .env file. - Hash passwords instead of storing them in 
plain text.

📈 Future Improvements

- SQLite/MySQL database integration
- Password hashing with bcrypt
- Email OTP support
- GUI using Tkinter or PyQt
- Web version with Flask/Django

👨‍💻 Author

Swapnil

If you found this project useful, consider giving it a ⭐ on GitHub!
