# Perfectly Secure Encryption- 

just a single html5 page (inline js) that is an ENHANCED One Time Pad- very nice. 

works in browser offline or online.

you can easily implement the idea here in any other script/lang. 

details are on bottom of the html page. 


# Perfect Secrecy:

A one time pad is theoretically unbreakable if the key is truly random, at least as long as the plaintext, used only once, and kept secret. This implementation adheres to these rules, assuming the key is generated and managed securely.

# Enhancement via IV:

Even though a true OTP does not require an IV, adding a full-length random IV here mitigates risks if the key is accidentally reused. It ensures that even identical plaintexts with the same key will produce different ciphertexts.

# Usage in Practice:

While this tool is a great demonstration of the OTP concept and encryption fundamentals, it’s primarily educational. In real-world applications, careful key management and additional security measures would be needed. Rust lang is probably the most reliable lang to make encryption apps with. 
