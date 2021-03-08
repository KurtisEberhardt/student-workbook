Day 1: 
1. What is the purpose of a Query String?
    A Query String allows you to add additional search information onto the end of the URL. 

2. What is the format of a query parameter? How does it start? How do you distinguish between one parameter and the next?
    The format of a query parameter is anything that comes after a ? in a URL. for example: ?ab=35 etc 
3. When do you think Query parameters would be helpful when writing your server?
    Query parameters basically allow you to make information easier to find and control the routing through your server to make it easier on yourself in the long run. 
Day 2:

1. What are the three types of relationships?
One to One, One to Many, Many to Many

2. What are the benefits of the traditional linking of relationships instead of Embedding
    
    The benefit of traditional linking is that additional comments won't grow the actual data post. 
3. What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
    
    The challenges are how to handle the amount of data that you may deal with and the kind of many to many relationship you choose to use can determine how you approach it. 

Day 3: 

1. In simple terms what is a sub-document?
    Sub document is are documents that are nested inside of other documents. 
2. When might you use a sub-document?
    You would use a sub-document to import more complicated objects without making one giant schema with a ton of individual objects
3. How do you add to a collection of sub-documents? What about editing them?
    You would need to create a new collection and then add in whatever you want. In order to edit it, you would use findOne and then add your changes, and save it. 


Day 4: 

1. What is a virtual property?
    A virtual property is an additional field for a given model. 
2. When might you use a virtual property?
    You would use a virtual property in order to write reusable code that you could use in multiple places. 
3. How do you search by a virtual properties value?
    You actually can't search by a virtual properties value. 