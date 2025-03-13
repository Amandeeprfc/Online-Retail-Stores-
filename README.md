# Online-Retail-Stores-
Online Retail Stores Using My SQL

1 - Write a query to display customer full name with their title (mr/ms), both first name and last name are in upper case with customer email id, customer creation date and display customer’s category after applying below categorization rules:
       
       i. If customer creation date year <2005 then category a
       
       ii. If customer creation date year >=2005 and <2011 then category b
       
       iii. If customer creation date year>= 2011 then category c

2. Write a query to display the following information for the products, which have not been sold:  product_id, product_desc, product_quantity_avail, product_price, inventory values(product_quantity_avail*product_price), new_price after applying discount as per the below criteria. Sort the output concerning the decreasing value of inventory_value.

   i. If product price > 20,000 then apply 20% discount

   ii. If product price > 10,000 then apply 15% discount

   iii. If product price =< 10,000 then apply 10% discount

 
 4. write a query to display product_class_code, product_class_description, count of product type in each product class, and inventory value (p.product_quantity_avail*p.product_price). 
   Information should be displayed for only those product_class_code that have more than 1,00,000 inventory value. sort the output concerning the decreasing value of inventory_value.

 
 5. Write a query to display customer_id, full name, customer_email, customer_phone and country of customers who have cancelled all the orders placed by them (use sub-query).
 
 6. Write a query to display shipper name, city to which it is catering, number of customer catered by the shipper in the city and number of consignments delivered to that city for 
    shipper dhl.
 
 7. Write a query to display customer id, customer full name, total quantity and total value (quantity*price) shipped where mode of payment is cash and customer last name starts with 'g'.
 
 8. Write a query to display order_id and volume of biggest order (in terms of volume) that can fit in carton id 10.
 
 9. Write a query to display product_id, product_desc, product_quantity_avail, quantity sold, and show inventory status of products as below as per below condition:
 
 a. For electronics and computer categories, 
    i. If sales till date is zero then show 'no sales in past, give discount to reduce inventory',
    ii. If inventory quantity is less than 10% of quantity sold, show 'low inventory, need to add inventory', 
    iii. If inventory quantity is less than 50% of quantity sold, show 'medium inventory, need to add some inventory', 
    iv. If inventory quantity is more or equal to 50% of quantity sold, show 'sufficient inventory'
 
 b. For mobiles and watches categories, 
    i. If sales till date is zero then show 'no sales in past, give discount to reduce inventory', 
    ii. If inventory quantity is less than 20% of quantity sold, show 'low inventory, need to add inventory',  
    iii. If inventory quantity is less than 60% of quantity sold, show 'medium inventory, need to add some inventory', 
    iv. If inventory quantity is more or equal to 60% of quantity sold, show 'sufficient inventory'

 c. Rest of the categories, 
    i. If sales till date is zero then show 'no sales in past, give discount to reduce inventory', 
    ii. If inventory quantity is less than 30% of quantity sold, show 'low inventory, need to add inventory',  
    iii. If inventory quantity is less than 70% of quantity sold, show 'medium inventory, need to add some inventory', 
    iv. If inventory quantity is more or equal to 70% of quantity sold, show 'sufficient inventory'

9. Write a query to display product_id, product_desc and total quantity of products which are sold together with product id 201 and are not shipped to city bangalore and new delhi. Display the output in descending order concerning tot_qty.(use sub-query)  

10. Write a query to display the order_id,customer_id and customer fullname and total quantity of products shipped for order ids which are even and shipped to address where pincode is not starting with "5" 
