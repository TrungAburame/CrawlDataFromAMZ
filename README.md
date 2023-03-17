# CrawlDataFromAMZ
Not all of the report on Amazon are available, sometimes we need to crawl it ourselves.

# Getting all the needed information for crawling data
All we need of course is the account name and password to login to Amazon website.
Secret key are also important because it will grants us OTP after login. So we don't have to do it manually.

![image](https://user-images.githubusercontent.com/72678942/225932209-1ff9b064-1416-4de9-b465-cbb5bc65b083.png)

I always have a function to generate data and another function to clean data. For the otp I use library pyotp in python.

![image](https://user-images.githubusercontent.com/72678942/225934232-db187bc6-65b8-4d63-8c67-1927bfd5239a.png)

The last step is to insert data into a table on Oracle. Here I have another file for the Oracle account but I wont upload it here due to security.

![image](https://user-images.githubusercontent.com/72678942/225934800-6cf11969-0b2b-4093-9fa0-a5435272240d.png)
