## What it does.
1. Builds a contact book from scratch.
2. Displays all contacts using a loop.
3. Loops through the contact book list by variable and outputs the results if it matches the search.

## Usage
``` python
print("\n=====NAIROBI CITY===== ")
for contact in contacts:
    if contact["city"] == "Nairobi":
        print(f"  {contact['name']} | {contact['phone']} | {contact['skill']}")
```
## Output
=====NAIROBI CITY===== 
  James Omodi | 0712345678 | welding
  Patrick Njiru | 0734567890 | phone repair
  Brian Kamau | 0756789012 | upholstery
##Stack
Python
