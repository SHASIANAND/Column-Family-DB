# Column-Family-DB

This schema includes three tables: 

         1)drugs
         2)orders
         3)customers. 

The drugs table stores information about each drug in the pharmacy, including its unique

          drug_id,
          name, 
          description, 
          quantity, and 
          price. 

The orders table stores information about each order placed by a customer, including its unique 

          order_id, 
          date, 
          customer_id, 
          items, and 
          total. 
          

The items field is a list of tuples that contain the drug_id and the quantity of that drug ordered. 

The customers table stores information about each customer, including their unique 

          customer_id, 
          name, 
          email, 
          phone, and 
          address.
          
          ![WhatsApp Image 2023-03-17 at 21 24 18](https://user-images.githubusercontent.com/113984771/225956270-1c613c0c-efcc-438c-8bc2-e13fe5b13e87.jpg)


The 'toTimestamp(now())' function call returns the current timestamp in Cassandra's internal format, which is used to record the date of the order.
