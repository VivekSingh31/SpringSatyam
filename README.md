1.open cmd an run command mvn clean install
2.Import project in ide.
3.Start spring boot project 
4.For data bases please access below url 
http://localhost:8081/h2-console
in Url filed 
 jdbc:h2:mem:books_data
![image](https://github.com/VivekSingh31/SpringSatyam/assets/69783301/a7466bc2-79b2-47a2-8c5d-eb441c684bb7)

5.Post request using postman 
http://localhost:8081/books
body>json 
{  
    "bookid": "0982",  
    "bookname": "Programming with Java",  
    "author": "E. Balagurusamy",  
    "price": "350"  
}   
{  
    "bookid": "6321",  
    "bookname": "Data Structures and Algorithms in Java",  
    "author": "Robert Lafore",  
    "price": "590"  
}   
{  
    "bookid": "5433",  
    "bookname": "Effective Java",  
    "author": "Joshua Bloch",  
    "price": "670"  
}  


5.To see data 
http://localhost:8081/book


