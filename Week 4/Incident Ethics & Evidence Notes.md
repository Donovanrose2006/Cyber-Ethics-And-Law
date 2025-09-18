# My First Hour Priorities
Items that would be most likely to be captured would be the network logs and screenshots or any other proof of the threat. These captures would not be too invasive and the network logs must use the minimum data necessary to understand the threat. Items to avoid would be any user documents or folders unrelated to any incident that occurred, as it would be a breach of privacy and cause legal risks.
# Incident & Evidence Note
I was told about the suspicious email by incident manager John Smith within 15 minutes of its receipt. John Smith created the work ticket and authorized inspections, after which I ran an SQL query to pull the login logs only for the recipient of the suspicious email. I also opened the attached file in a quarantined virtual machine browser and was presented with an obviously fake login page. The file hash is 23f9985b71f3b714172addc83c0158a00cf99193f7cac42c52b6aeefb6fdf48a. The recipient of the email should be contacted right away, as it looks like the account may have been breached. It’s likely the user attempted to log in on the fake page, which would have sent their credentials to a third party. The account should be locked immediately, logged out on all devices, and the password reset.
# Integrity and Privacy Controls
Hashing is a cryptographic identifier of a file, not encryption. A hash is different after any change made to it. Storage location of evidence is very important, as it shouldn’t end up in the wrong hands. Data should be kept in a private area and should not be accessed unless necessary. Redactions are also important for moments where data needs to be removed to keep confidentiality. 
# Evidence Links
https://docs.google.com/document/d/1-91eQB2RBZTq5CYnBzW9DLgltpcjFPrAnkTlBAPfppo/edit?tab=t.0
# Reflection
I wish I had more to work with for the in-class activity, it seemed like it was left pretty vague and it was clear there still technically could be other options for what really happened. I would've enjoyed more to work with, so within the activity itself, I would keep an eye on the ticket for the case itself.
# AI Use Note
I used AI to help me streamline my Incident & Evidence Note into a more streamline paragraph.
