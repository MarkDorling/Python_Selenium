# Python_Selenium
<b>Using Python 3 with Selenium.</b><br>
<br>
<i>This is an anonymised project that combines code written for two unrelated projects for clients in 2022.</i><br>
<br>
<b>Background:</b> My commissioning clients requests: <br>  
Client 1) To automate test cases for web browsers to simulate tests such as tapping on a button, entering content to the structures,  etc. <br>
Client 2) A data acquisition solution; <br><br>

<b>Problem:</b> The rapid development of new scripts required menus to be continually updated (adding, removing, and reordering menu items) leading to:<br>
• Continuity issues between menu options and associated functions;<br>
• Lengthy and inelegant code;<br>
• Duplication of menu related code;<br>
• Errors in program structure.<br>
<br>
<b>Client solution - Main:</b> I created a command line menu system underpinned by a dictionary data structure. The main menu, all sub-menus and menu items (menu option descriptions and associated function names) are stored in the dictionary. Please see the commented code for more details on how it works.<br>
<br>
<b>Generalised solution - Branch <i>( Generalised version with dynamic module names)</i>:</b> This is a generalised version of the main project that uses dynamic module names. In particular, the names of the dynamic module names (e.g. generic_tasks.py and generic_dictionary.py) are passed as arguments directly into the display_menu function within the interface.py; This allows this command line project to be used by anyone with their own dictionary and tasks py files. Furthermore, I also removed the selected_menu_number from the argument passed into the display_menu function within the interface.py; instead the variable is declared (with first number number) before the while loop; the selected_menu_number variable is updated within the loop as previously. <br>
<br>
<b>Config overview:</b><br>
• conda version : 23.1.0<br>
• conda-build version : 3.23.3<br>
• Python version : 3.9.16 <br>
• Requirements.txt <i>contains all library, packages and modules information</i>



