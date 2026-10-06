HTTP Strict Transport Security

Web security mechanism that tells a browser only to comm with a website using HTTPS

Enabled via the Strict-Transport-Security header in the response

Ex `Strict-Transport-Security: max-age=31536000; includeSubDomains` tells the browser to use HTTPS only for the next year

Biggest issue is the "first visit" problem, where a user visits the site for the first time and thus the browser doesn't know to use HTTPS

Helps against [[downgrade attack]]s