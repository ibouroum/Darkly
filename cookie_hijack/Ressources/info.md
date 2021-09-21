# EXPLANATION
The Session Hijacking attack consists of the exploitation of the web session control mechanism, which is normally managed for a session token.
The Session Hijacking attack compromises the session token by stealing or predicting a valid session token to gain unauthorized access to the Web Server.

When I checked the cookies I found a cookie named 'I_am_admin' which has as a value 68934a3e9455fa72420237eb05902327, I decrypted it using md5 and it gave "false".
So I encrypted "true" using md5 and replaced the value of the cookie.

# UTILITY

Cookie hijacking is the exploitation of a valid computer session—sometimes also called a session key—to gain unauthorized access to information.

# HOW TO AVOID ?

Avoid storing sensitive data in the cookies. And opt for a more secure encryption protocol :)