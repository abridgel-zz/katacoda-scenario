Login to the contrast platform at:

https://apptwo.contrastsecurity.com

With the credentials you were provided with. Ensure your application has been onboarded

Now we will need to trigger an SQL Injection per the following steps

1. Try to login into juice-shop
2. In the username field enter the following text

	'OR 1=1 --

3. Add any text into the password field and click login

This should trigger an SQL Injection. Find the SQL injection in CONTRAST and confirm it has indeed been triggered

If your having problems triggering the SQL Injection here is a short clip from youtube that can help:

<iframe width="560" height="315" src="https://www.youtube.com/embed/cXoA-Dge2B0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
