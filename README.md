# SALES_TAXES
An Application that prints out the receipt of Goods details


Basic sales tax is applicable at a rate of 10% on all goods, except books, food, and medical
products that are exempt. Import duty is an additional sales tax
applicable on all imported goods at a rate of 5%, with no exemptions. When I purchase items
I receive a receipt which lists the name of all the items and their price (including tax),
finishing with the total cost of the items,
and the total amounts of sales taxes paid. The rounding rules for sales tax are that for a tax
rate of n%, a shelf price of p contains (np/100 rounded up to the nearest 0.05) amount of
sales tax.



I used <br />
1-Apache NetBeans IDE 15 <br />
2-XAMPP Control Panel -->Mysql<br />

For Download the Application , you have to open SellingAppSetup folder , then you will find file with .exe extension. <br />
when you download it , you can click on Buttons to buy a Products , It is displayed in a table, consisting of the product name, quantity, price and finally the last column to know the price of the added tax.<br />

Print Button --> print out the receipt details <br />
Reset Button --> The Table will be empty<br />
Remove Button--> remove selected Row <br />
Exit  Button -->to close the Application<br />

For XAMPP, I signed a database via MySQL, I wanted to add new features to the program in the future such as delete and add.There are some functions in code source.<br />
which are :-<br />
       // CreateDb(); <br />
       // Create_goods_table();<br />
       // initialize_goods_table();<br />
       <br />
       if you want to run the code source , open ITEMS folder in Apache NetBeans IDE then run Main.class<br />
