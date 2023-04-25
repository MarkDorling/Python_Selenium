# Python_Selenium
<b>Using Python 3 with Selenium.</b><br>
<br>
<i>This is an anonymised project that combines code written for two unrelated projects for clients in 2022.</i><br>
<br>
<b>Background:</b> My commissioning clients requests:  
Client 1) To automate web browser test cases for their website; <br>
Client 2) A data acquisition (scraping) solution e.g. supplier product prices. <br>
<br>
<b>Problem:</b> ..............................................................................:<br>
• To automate (and simulate) tests such as tapping on a button, entering content to the structures etc;<br>
• To prevent the IP address being blocked due to multiple visits to the same website;<br>
• To Maintain IP address privacy;<br>
• To scrape and store data acquired in a json file;<br>
<br>
<b>Client solution:</b> I created a Python 3 with Selenium (using xpath) script. The structure of script encourages generalisation for use in other projects easier. It includes functions for: <br>
• Anonymised opening of the web browser (using a proxy server);<br>
• Applying delays (varying lengths) between actions;<br>
• Setting browser size;<br>
• Logging-in and out;<br>
• Rejecting pop-ups;<br>
• Navigating between pages using weblinks;<br>
• Using the browser 'Back' button;<br>
• Scrapping data;<br>
• Closing the browser.<br>
Please see the commented code for more details on how it works.<br>
<br>
<b>Config overview:</b><br>
• conda version : 23.3.1<br>
• conda-build version : 3.23.3<br>
• Python version : 3.9.16 <br>
• Requirements.txt <i>contains all library, packages and modules information</i>



