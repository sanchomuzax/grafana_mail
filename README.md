# grafana_mail

* Sending an e-mail report on yesterday's tables
* Require python module `requests`

Parameters:
~~~
-h HELP
-f MAIL_FROM 
-m MAIL_LIST or MAIL_LIST
-M MAILHOST 
-G GRAFANA_SERVER 
-P PANEL_LIST 
-T API_TOKEN 
-W IMG_WIDTH 
-H IMG_HEIGHT
~~~

Example of usage:

~~~
./grafana_mail.py -m mail1@domain.test mail2@domain.test -f mailer@domain.net -M mailhost.domain.test -G http://localhost:3000 -P dashboard1,1 dashboard2,14 dashboard4,1 dashboard6,2
~~~
