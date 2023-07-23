Domain:

1. Register a Domain
You can register domain in many places, such as Google Domains or GoDaddy.

2. Point your Domain
Once you've registered your domain, click Domains in the menu and choose your domain.
Then click on 'Manage DNS Records'
Now locate the HOSTNAME form
And enter the following details:
Hostname: www
Type: CNAME
Value: your domain from PythonAnywhere (for example djangogirls.pythonanywhere.com)
TTL: 60
Click add button and save changes

3. Configure domain in PythonAnywhere
First, upgrade your account if it is a free account.
Next, go over to the Web tab.
Copy the path to your virtual environment and paste it somewhere.
Click on your wsgi config file, copy it, and paste it somewhere.
Delete your old web app.

4. Create new web app
Create a new web app by entering the following information:
Enter your new domain name
Choose "manual configuration"
Pick Python 3.4

Go back to the web tab, paste in the virtual environment path, and paste in contents from config file

You're finished.








