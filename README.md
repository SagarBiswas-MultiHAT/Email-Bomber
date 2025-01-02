# Email Bomber  

This Python script automates sending multiple emails to a specified recipient using Gmail's SMTP server. It supports HTML-formatted messages, customizable subjects, and email body content. **This tool is for educational purposes only. Please use responsibly and adhere to ethical and legal guidelines.**  

## Features  
- Send bulk emails to a target email address.  
- Customize email subject and body content.  
- Supports HTML formatting for email body.  
- Simple configuration and usage with Gmail's SMTP server.  

## Prerequisites  
1. Python 3 installed on your system.  
2. A Gmail account with "App Passwords" enabled.  
   - [Learn how to generate an app password](https://support.google.com/accounts/answer/185833).  

## Installation  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/your-username/email-bomber.git  
   cd email-bomber  
   ```  
2. Install dependencies (if not already installed):  
   ```bash  
   pip install smtplib  
   ```  

## Usage  
1. Open the script in your preferred text editor.  
2. Update the following variables in the script:  
   - `to_email`: Target email address.  
   - `from_email`: Your Gmail address.  
   - `app_password`: Your Gmail app password.  
   - `subject`: Subject line for the email.  
   - `body`: HTML content of the email body.  
   - `num_emails`: Number of emails to send.  
3. Run the script:  
   ```bash  
   python email_bomber.py  
   ```  

## Example  
Here's an example of how to configure the script:  
```python  
to_email = "target@example.com"  
from_email = "your-email@gmail.com"  
app_password = "your-app-password"  
subject = "Friendly Reminder!"  
body = "Don't forget to smile today! 😊"  
num_emails = 50  
```  

## Legal Disclaimer  
This script is intended for educational purposes only. Unauthorized use of this script to send unsolicited emails or perform email bombing attacks is strictly prohibited and may violate local, national, or international laws. **The creator is not responsible for any misuse of this code.**  

## License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
