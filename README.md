# Privilege-escalation-in-online-jewelry-website
Vertical Privilege Escalation vulnerability found in Online Jewellery Store from Sourcecodester website.


Description: Vertical Privilege Escalation vulnerability found in Online Jewellery Store from Sourcecodester website.

[Additional Information] NA

[Vulnerability Type] Vertical Privilege Escalation 

[Vendor of Product] https://www.sourcecodester.com/

[Affected Product Code Base] Online Jewelry Shop using PHP/MySQLi with Source Code

[Affected Component] http://localhost/jewelry/admin/index.php?page=category_list

[Attack Type] Remote

[Impact Information Disclosure] True

[Attack Vectors] Steps to reproduce: 
Login with user credentials in one browser (Chrome)
Login with admin credentials in another browser (Firefox)
In Firefox browser click on Categories - Add New and copy the link http://localhost/jewelry/admin/index.php?page=new_category
Navigate to Chrome where we logged in as a user and observe we don't have the functionality for the user to add categories. Paste the link we copied from Firefox in Chrome.
Enter any category name and click on Save. The category name will be saved. 

[Discoverer] M Lohith
