# Anti-64
Created by @johnjhacking

This script was built for those tough Base-64 Situations, especially during CTF events. I ran into a situation where I had obviously Nested Base64 (and the hint said it was encoded 13 times) and all of the tools I attempted to use were not working.

# Usage
It's fairly easy to use:
1. Edit the script with your favorite editor
2. In the inp_string variable, remove the current Base64 code between the quotation marks and add your own!
3. In the for loop, specify how many times you need it to run (currently set to times = 13)
4. Run the Script
5. python anti-64.py
6. **Profit**

# Considerations
If you do not use the correct amount of times to run the decode on the Base64 code; you will break the script. 
This will be indicated by a TypeError: "Incorrect Padding"
