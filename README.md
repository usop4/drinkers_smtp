# drinkers_smtp

smtp relay with alcohol sensor

## Description

drinkers_smtp run as smtpd and insert stupid header into email.

based on
https://hg.python.org/releasing/2.7.9/file/tip/Lib/smtpd.py

## Requirement

Python 2.x

## Usage

Download smtpd.py and run

> python smtpd.py -n -d localhost:8025 your.mailserver:587

Configure your email client to connect localhost:8025 and send mail.

## Link

酒を飲みながらメール送信すると酔い具合がメールヘッダに記録されるリレーサーバ
https://deisui.amebaownd.com/posts/33866
