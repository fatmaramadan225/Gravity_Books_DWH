# Gravity_Books_DWH

Gravity Bookstore is a database for a fictional bookstore called that captures information about
books, customers, and  sales

### ERD of ‘gravity_books’ transactional database:
![Untitled](https://github.com/user-attachments/assets/95f795e8-9de9-415e-9ad1-122ef67d8b31)

### Tables description:
**book:** a list of all books available in the store.\
**book_author:** stores the authors for each book, which is a many-to-many relationship.\
**author:** a list of all authors.\
**book_language:** a list of possible languages of books.\
**publisher:** a list of publishers for books.\
**customer:** a list of the customers of the Gravity Bookstore. \
**customer_address:** a list of addresses for customers, as a customer can have more than one address, and an address has more than one customer.\
**address_status:** a list of statuses for an address, because addresses can be current or old.\
**address:** a list of addresses in the system.\
**country:** a list of countries that addresses are in.\
**cust_order:** a list of orders placed by customers.\
**order_line:** a list of books that are a part of each order.\
**shipping_method:** the possible shipping methods for an order.\
**order_history:** the history of an order, such as ordered, cancelled, delivered. \
**order_status:** the possible statuses of an order

## Gravity_Book_DWH Design
#### Galaxy Schema

![Untitled2](https://github.com/user-attachments/assets/f156336e-c5ec-42e1-9349-4b98433f96e8)

### Dashboard

![Screenshot 2024-09-11 113512](https://github.com/user-attachments/assets/fd09e02c-79bb-4f78-ae92-6fe6c4750a4a)


**Total Sales:** 84.23K\
**Delivered:** 2995 orders have been successfully delivered.\
**Pending Delivery:** 6800 orders are awaiting delivery.\
**Delivery in Progress:** 3459 orders are currently in the delivery process.\
**Cancelled:** 300 orders were cancelled.\
**Received:** 7544 items have been received by customers.\
**Returned:** 194 items have been returned.\
**Total Sales by Year:** A line graph displaying monthly sales data for the year.\
o Sales show fluctuations, with a peak in August (13.9K) and lower sales in January (12.6K).\
**Delivery by Shipping Method:** A pie chart showing the distribution of delivery methods:\
**o Express:** 47.38%\
**o Standard:** 39.8%\
**o International:** 12.32%

![Screenshot 2024-09-11 113556](https://github.com/user-attachments/assets/06a8eaf7-d8f1-44c4-bdc8-b9f967753544)


**Count of Books:** 11.13K total books in the system.\
**Languages:** 27 different languages available.\
**Publishers:** 2251 different publishers.\
**Authors:** 9235 different authors are represented.\
**Count of Books per Language:**\
 English leads with 8911 books, followed by US English (1409), Spanish (218), British
 English (214), and French (144)\
**Sum of Price by Title:** A bar chart showing prices by book titles, where popular titles
like The Odyssey, Salem’s Lot, and Anna Karenina are priced around 149-121 units.\
**Count of Books by Publisher:** A bar chart showing books distributed by publishers
o Vintage leads with 318 books, followed by Penguin Books (261), Penguin Classics (184), and other major publishers like Mariner Books (150) and  and HarperCollins (111).

![Screenshot 2024-09-11 113640](https://github.com/user-attachments/assets/f1ef3015-1057-4dbc-bba7-6f01451ddd7a)

**Customers:** A total of 2000 customers.\
**Customers per Shipping Method:** A bar chart showing customer distribution by shipping
method:\
**Express:** 3.5K customers.\
**Standard:** 3.0K customers.\
**International:** 1.0K customers.\
**Priority:** 0.1K customers.\
**Customers per Country:** A bar chart showing customer distribution by country:\
 China has the largest customer base (321), followed by Indonesia (217), Russia (122), Brazil
(71), and smaller distributions across other countries like Philippines, Poland, and USA.\
**Sum of Cost by Shipping Method:** A bar chart showing costs by shipping method:\
**International:** 25 units.\
**Express:** 12 units.\
**Priority:** 9 units.\
**Standard:** 6 units.\
**Orders per Customer:** A bar chart and line graph showing orders per customer.
