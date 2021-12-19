# What is ***Variable***?
  >Variable is a name given to a storage in memory(which value can be changed) 
 
# What is ***Constant***  
  >Constant is an immutable value.(to mnake the program safe)  

# What are the types of Variable and Constant?
  >Primitive Types  
  >- Integral Numbers  
  >     - **byte**  &ensp; &nbsp;  &nbsp; 1byte  &nbsp;  &nbsp;  &nbsp;0--255
  >     - **short**  &nbsp; &nbsp; &nbsp; 2bytes  &nbsp;  &nbsp; -32768--32767
  >     - **int**   &nbsp; &nbsp; &nbsp;  &nbsp;  &nbsp; 4bytes 
  >     - **long** &nbsp; &nbsp; &nbsp; 8bytes 
  >- Real Numbers  
  >     - **float**  &nbsp;  &nbsp;  &nbsp; 4bytes 
  >     - **double**  &nbsp; 8bytes
  >     - **decimal**&nbsp; 16bytes 
  >- Character  
  >     - **char**  &nbsp;  &nbsp;  &nbsp; 2bytes
  >- Boolian      
  >     - **bool**  &nbsp;  &nbsp;  &nbsp; 1byte
    
  > **tips**:
  > 1. when we use **float** and **decimal**, add **f** and **m** after the data, because the default type of real number is double.
  > 2. keyword **var** can replace all decalre keyword and if use the **var** the default type of integral is **int**  
# How to declare a variable and constant?
  >For Variable: **Keyword Identifier = data;**  
  >For Constant: **const Keyword Identifier = data**

  >For Identifier:
  >1. Cannot start with a number
  >1. Cannot include a whitespace  
  >2. Cannot be a researved keyword
  >3. Use meaningful names  
  
# There are three naming conventions  
  >1. Camel Case: **f**irst**N**ame (the first word uses low case and any other use high case of their first letter)
  >1. Pascal Case: **F**irst**N**ame(all words use high case of their first letter)
  >1. Hungarian Notation: strFirstName  

  >For local variables: Camel Case  
  >For constants: Pascal Case

# What is the scope of Variables and Constants?
```
{                       block 1
  int a = 1;  
    {                   block 2
      int b = 2;  
       {                block 3
        int c = 3;  
        }  
     }  
 }
 ```  
>a is accessible in block 1,2,3  
>b is accessible in block 2, 3  
>c is accessible in block 3  


