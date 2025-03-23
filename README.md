# Password-Generator.
import random
import string
USERNAME=input("Enter your name:")
password=string.ascii_letters+string.digits+string.punctuation
passwordoutput=' '.join(random.choice (password) for _ in range(2))
print("THE GENERATED PASSWORD IS:",passwordoutput)
GENERATED=input("ENTER YOUR PASSWORD:")
if(passwordoutput==GENERATED):
    print("Name:K.Harini \n H.T.No :23D01A6688\nAadhar No:751* **** **09")
else:
    print("INVALID CAPTCHA")
