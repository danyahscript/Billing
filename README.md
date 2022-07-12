# Billing 

Billing is a Supermarket Basic Billing System written with Java Object-Oriented-Programming(OOP) and Java Database Connectivity(JDBC) including GUIs, specialized in billing where it organizes a medium-sized grocery store, with an appropriate and clear interface to navigate it. It is mainly used by either the cashier or the manager to input purchases and item information into the system.


The system is available for an `administrator, Cashiers, and Stock Clerks`  with different privileges. The ` administrator`  has an overall control over the system, where it registers employees along with their jobs. The ` Stock Clerks`  can add, delete, and update items along with their related information into the system, while the ` Cashiers` in turn responsible of the check-out process for the purchased items.

## System Constraints:
```
1. Administration must give employee (1) privileges to add offers. 
2. Administration must give employee (2) in check out stock.
3. Pices in the system must be updated after an offer has been added.
4. Each employee needs an ID number to log onto the system.
5. The user ID should Contain 10 digits.
6. The user’s password should Contain 8 digits with both letter and numbers.
```

## Demo

> the `Login` interface will let the user to select its role to provide their valid credentials.

<img width="501" alt="Login Interface" src="https://user-images.githubusercontent.com/74468149/178477553-262a0616-66b5-4f94-94c7-629572af2caa.png">

> If the `Stock Clerk` logs on, the `Product` interface will appear to perform addition, modification, and deletion on the items.

<img width="501" alt="Product Interface" src="https://user-images.githubusercontent.com/74468149/178477843-467d6323-d605-4e94-902d-9b486d5dab61.png">

<img width="501" alt="Product Interface" src="https://user-images.githubusercontent.com/74468149/178478008-e9f4c080-0d75-49ba-853c-ff74a7c6bf41.png">

<img width="501" alt="Product Interface" src="https://user-images.githubusercontent.com/74468149/178478017-f5dd339f-d4ea-495f-b7b2-8fbb975753bf.png">

> If the `Cachier` logs on, the `Customer Info.` interface will appear to perform addition and deletion of customer information, and choosing their Membership. `Choose Button` will open the `Card Membership interface`.

<img width="501" alt="Customer Info. interface" src="https://user-images.githubusercontent.com/74468149/178479074-a1403c1e-5daa-4dd6-a1e8-5d543ba154d3.png">

<img width="501" alt="Customer Info. interface" src="https://user-images.githubusercontent.com/74468149/178479087-1886b261-65b2-4fd9-8e85-8f9d5027a359.png">

<img width="501" alt="Customer Info. interface" src="https://user-images.githubusercontent.com/74468149/178479103-39972dbb-75bf-413c-bf5d-e6d1fbe3e740.png">

> After adding the customer, the `Cachier` can navigate to the `Billing` interface. This interface capable to perform filteration on the products, abd adding them to the bill.  ` The bill will be exported to a file inside the project whenever the Cachier clicks done`.

<img width="501" alt="Billing Interface" src="https://user-images.githubusercontent.com/74468149/178479628-c5f53960-c9b1-4bcf-bc19-aa1c300014cc.png">

> If the `Administrator "Manager"` logs on, the `Welcome` interface will appear which enable the admin to have an overlook through the system. 

<img width="501" alt="Welcome Interface" src="https://user-images.githubusercontent.com/74468149/178480458-db82bff1-aa2f-44f8-b714-e7097c6d8757.png">

<img width="501" alt="Welcome Interface" src="https://user-images.githubusercontent.com/74468149/178480479-89f600f3-e12d-4231-8f6a-4fa5f1778909.png">

> In `Manage Seller` interface, manager can control the employees (Add, Edit, and Delete).

<img width="501" alt="Manage Seller Interface" src="https://user-images.githubusercontent.com/74468149/178480986-45946e7c-1d6b-4b4d-b00d-e1753d1d5185.png">

> If `Administrator "Manager"` instead chooses to access the `Bills` interface, the system will ask to provide the customer ID before showing and processing the bill.

<img width="501" alt="Bills Interface" src="https://user-images.githubusercontent.com/74468149/178481411-adae2db7-a53b-4f5b-b788-f69d9a20879e.png">





