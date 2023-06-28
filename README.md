# Darryls-Email-Composer
My personal Email Composer I am constantly working on improving for easier email composer, all suggestions/bug reports/etc greatly appreciated. Please read LICENSING to see fair use.

**HOW TO USE:**
1. Edit config.ini file with your details for your email server and address
2. Edit email_template.txt to the template you wish to use, The variables can be placed anywhere but do not remove them or delete them 

**Example template:**

Dear {Recipient},

I hope this email finds you well. I wanted to reach out to you with the following information:

{AdditionalInfo}

If you have any questions or need further assistance, please let me know.

{Closing}

Best regards,
Your Name

Config.ini file example:

[SMTP]
server = smtp.example.com (your server)
port = 587/25/465 (protocol used, recommend starttls)
username = your@email.com (your email)
password = password (email password OR app password depending on auth method)

Thank you for your support and any issues I can be reached via github! https://github.com/sargetun
