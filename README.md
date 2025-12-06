# passwordstrenghtchecker
---------------------------
This Python script evaluates the strength of a password based on specific criteria. 
It classifies passwords into strong, moderate, or weak categories using regular expressions.
------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------
📌 Features
Strong Password Requirements

A password is considered strong if it:

Has at least 8 characters

Contains at least one uppercase letter

Contains at least one lowercase letter

Contains at least one special character (@$!%*&)
-------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------
Moderate Password Requirements

A password is considered moderate if it:

Has at least 6 characters

Contains at least one letter

Contains at least one number

Contains only letters and digits
--------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------
Weak Password

Any password that does not meet the above criteria is classified as weak.
---------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------
Example Outputs

Password	=  Strength
Abc@1234	=  Strong
abc123	  =  Moderate
abc       =	 Weak
------------------------------------------------------------------------------
------------------------------------------------------------------------------
📌 Notes

You can customize the regex patterns to add more rules (e.g., minimum digits, no spaces, etc.).

This is a simple client-side validator; do not use it as a security system for real-world authentication.
