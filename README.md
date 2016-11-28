# MassMailer-toolkit
100% python all-in-one mailing solution.

- Email extractor

- SMTP Checker

- Mailer

#
# Email extractor
[python3 emailparser.py http://foo.bar/crawlme max_pages output_file]

http://foo.bar/crawlme - URL of site with emails. Crawler will automaticaly extract all urls from web page and parse it.

max_pages - Maximum amount of pages to crawl.

output_file - Emails will be writen to this file line by line.

#
# SMTP Checker
This script checks SMTP servers.
[python3 smtpchecker.py file_with_SMTPs]

file_with_SMTPs - Text file with SMTP servers separated by line (password:login:host:port)

#
# Mailer
mailer.py
