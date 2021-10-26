# pattren

1)
```
n=7
for num in range(n):
    for i in range(n):
        print('*', end=' ')
    print()
 ```   
    
```  
* * * * * * * 
* * * * * * * 
* * * * * * * 
* * * * * * * 
* * * * * * * 
* * * * * * * 
* * * * * * * 
```
2)
```
n=7
for num in range(n):
    for i in range(num):
        print('*', end=' ')
    print()
 ```   
    
```  
* 
* * 
* * * 
* * * * 
* * * * * 
* * * * * * 
```
3)
```
n=7
for num in range(n):
    for i in range(num):
        print('*', end=' ')
    print()
 ```   
    
```  
* * * * * * * 
* * * * * * 
* * * * * 
* * * * 
* * * 
* * 
* 
```
4)
```
n=7
for num in range(n):
    for i in range(num,n):
        print(' ',end=' ')
        
    for i in range(num+1):
        print('*',end=' ')
        
    print()
 ```   
    
```  
              * 
            * * 
          * * * 
        * * * * 
      * * * * * 
    * * * * * * 
  * * * * * * *
```
5)
```
n=7
for num in range(n):
    for i in range(num,n):
        print('*',end=' ')
        
    for i in range(num+1):
        print(' ',end=' ')
        
    print()
 ```   
```  
* * * * * * *   
* * * * * *     
* * * * *       
* * * *         
* * *           
* *             
*       
```
