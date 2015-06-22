# phalcon_1.3.4
Phalcon 1.3.4 DLL for Windows and XAMPP

# Setting up

1. Download the zip file (Should come up as phalcon_1.3.4.zip)
2. Extract the folder into your Downloads folder or directory of your choosing (i.e. Desktop)
3. Open the extracted folder and copy 'php_phalcon.dll'.
4. If you are using XAMPP, paste into 'C:\xampp\php\ext' or appropriate PHP extensions folder.
5. Go into 'C:\xampp\php' and open up a file named 'php' or 'php.ini' with 'Configuartion Settings' in the 'Type' column.
6. On the last line of the entire file enter 'extension=php_phalcon.dll' (without the quotes).
7. Save and Close the file.

# Testing it out with phpinfo

1. Go to localhost in your web browser.
2. Click on phpinfo() link on the left panel of the xampp page (Under demos) 
3. You should see the following details for phalcon: 
  phalcon

  Phalcon Framework	enabled
  Phalcon Version	1.3.4
4. Your phalcon projects should work now. Enjoy!
