# Password-Generator.
import random
import string
USERNAME=input("Enter your name:")
password=string.ascii_letters+string.digits+string.punctuation
passwordoutput=' '.join(random.choice (password) for _ in range(2))
print("THE GENERATED PASSWORD IS:",passwordoutput)
GENERATED=input("ENTER YOUR PASSWORD:")
if(passwordoutput==GENERATED):
    print("Name:K.Hari \n H.T.No :12345678\nAadhar No:7*** **** ***9")
else:
    print("INVALID CAPTCHA")
