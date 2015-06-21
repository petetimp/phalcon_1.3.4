# phalcon_1.3.4
Phalcon 1.3.4 DLL for Windows and XAMPP

Setting up

1. Download the zip file (Should come up as phalcon_1.3.4.zip)
2. Extract the folder into your Downloads folder or directory of your choosing (i.e. Desktop)
3. Open the extracted folder and copy 'php_phalcon.dll'.
4. If you are using XAMPP, paste into 'C:\xampp\php\ext' or appropriate PHP extensions folder.
5. Go into 'C:\xampp\php' and open up a file named 'php' or 'php.ini' with 'Configuartion Settings' in the 'Type' column.
6. On the last line of the entire file enter 'extension=php_phalcon.dll' (without the quotes).
7. Save and Close the file.

Testing it out with phpinfo

1. Open up a new file using your text editor of choice (Notepad is a good choice).
2. Insert the following code
    <?php 
      phpinfo();
    ?>
3. Save the file as 'info.php' in C:\xampp\htdocs\ and go to localhost\info.php in your web browser.
4. Press ctrl+f and search for 'phalcon'
5. You should see the following details: 
  phalcon

  Phalcon Framework	enabled
  Phalcon Version	1.3.4
6. Your phalcon projects should work now. Enjoy!
