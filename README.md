# ETG-Inventory-management-assignment:
This is the repository created to achive a sample model of inventory management system during the ETG skill India internship
Dwells with the basic and crucial functionality how an inventory that is used in a supermarket or any other department is managed during the purchase of product by customer,admin management and few other important concepts.

### Features of  inventory
1.purchase of goods
   --> simultaneous reduction of quantities in inventory  and  incrementation in customer purchase good
2.automatic generation of goods receipt
3.automatic report generation for expiry products
4.automated alerts in case when inventory is about to be out of stock
5.possible error occuring is managed 
6.restrictions when an expired product is tried to be sold

### Pakages and modules involed
1.datetime
2.json
3.string
4.random 
5.time

### Files used:

#### 1.record.json
    --> records all the updation,deletion,incrementation during loading goods,new item entry,decrementation during the purchase
    --> records are stored in nested dicitionary manner where product id is taken as key and dictionary of product name ,unit price quantity in stock ,pakage date,inventory value of the product acts as value
    --> record is ordered in the following manner
            record={"p_id1":{"name1":"abc","unit_price":12,"quantity_in_stock":123,"pakage_date":"12/02/2021","inventory_value1":124},"p_id2":{"name2":"as",.....}}
    -->attributes involved
           product id
           product name
           unit price of product
           pakage date
           total inventory value


#### 2.sales.json
      --> records all the sales and transcation made in the inventory where only updation is made no removal or correction can be made 
      -->sales are also recored in  the manner of nested dictionary where, transcation id plays the role of main key and the name,quantity bought and total amount are keys of nested dictionary whose corresponding values are stored in list
      --> sales is ordered in the following manner
       sales={"transcation_id1":{"name1"=[ "a","b","c"],"quantity1":[1,2,3],"amount":[12,23,40],"total_amount1":12+23+40},"transcation_id2":{"name2:....}}
      --> attributes involved
          transcation id
          product names
          quantity purchsed
          amount of each product
           total amount



#### 3.expiry.json
      --> records all the expired products and products that would expire in short period of time
      --> expiry recored in the same nested dictionary manner where contains two keys expired and about to be expired which coressponds to nested dicitonary which again has product id and product name 
      -->expiry is ordered in the following manner 
       expiry={"expired":{p_id1:name1,p_id:name2,...},"about to expire":{p_id3:name3,p_id4:name4,.......}}
      --> Atttributes involved
             product id
             produc name
   
   
## who I am ?
 My name is S.Oviya Retheneka and I am a student currently persuing B.Tech second year at Kumaraguru college of technology.
 I am also passionate about learning skillsets about AI and ML 
 
