# EXPLANATION

In the recover password page http://10.12.100.231/index.php?page=recover

If we inspect the form we find a mail hidden input , when changing it's value and submitting we get the flag.

# UTILITY

Some websites and applications embed hidden fields within web pages to hack and pass state information between the web server and the browser.
Hidden fields that contain confidential information (such as product prices on an e-commerce site) should be stored only in a back-end database.

# HOW TO AVOID ?

Avoid passing such information using hidden fields. In our case the admin email can be used directly in backend.