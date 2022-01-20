# **Password generator**

This program interacts with the user by letting it choose what kind of password they want. 
You can choose between the difficulty of _easy_, _medium_ or _hard_ which the creator of the program have decided what the definition they all have.

## **Definitions of password**
- Easy - contains four digits and four letters with a total length of 8.\n
- Medium - contains five digits and five letters with atleast 2 upper and lowercase with total length of 10.
- Strong - contains five digits and five letters with atleast 2 upper and lowercase a total and two special characterwith length of 10.

The user can also choose to customize the password by combining upper and/or lowercases with digits and special characters.

## **Saving**
Once the user generate a password the program will then ask what the of the password should be, whatever it should be used for twitter or netflix i.e. 
The data is then saved into a DataFrame which is created by using Pandas. The data is connected to a CSV-file. 
The user can any time find its passwords in the CSV-file. If the user decides to delate all of the password they can just simply clear the CSV-file in the program.
