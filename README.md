### SMTP
---
Simple Mail Transfer Protocol




```
S: 220 foo.com ESMTP Postfix 
C: EHLO example.com
S: 250 foo.com greets example.com
C: MAIL FROM:<sender@example.com>
S: 250 Ok
C: RCPT TO:<receiver@foo.com>
S: 250 Ok
C: DATA
S: 354 End data with <CR><LF>.<CR><LF>
C: From: Sender Example <sender@example.com>
C: To: Receiver Example <receiver@foo.com>
C: Date: Tue, 15 Jan 2008 16:02:43 -0500
Subject: Test message
C:
C: Hello Alice.
C: This is a test message with 4 header fields and 4 lines in the message body.
C: Your friend.
C: Bob
C: .
S: 250 Ok
C: QUIT
S: 221 Bye
```

```
```

```
```


