# Level Based Persona
[people-43575_960_720](https://cdn.pixabay.com/photo/2012/04/28/17/11/people-43575_960_720.png)
## Business Problem & Purpose

To make new customer definitions by using the characteristics of individual customers  **(level based persona)**.

Segmenting new customer definitions.

Integrate system with the new future users.  

------

## Project Steps

- Thinking about the concept of persona.
- To be able to define new customers according to the levels.
- Simply segment new customer definitions using the qcut function.
- When a new customer arrives, classify them according to segments. 


## Dataset Information

There are two different tables showing the customers' characteristics and transaction information. 

**users.csv** shows the characteristic features of the customers, 

**purchases.csv** shows the transaction information of the customers.

Each user has a unique customer number (**uid**). 

The process of combining both tables can be done with the (**uid**) number. 

---

## Features

**users.csv**

- **uid**: Unique ID belonging to customers
- **reg_date:** Registration dates of customers
- **device**: Devices used by customers ( Android, iOS ) 	
- **gender**: Genders of customers
- **country**: Countries where customers reside
- **age**: Ages of customers

**purchaces.csv**

- **uid**: Unique ID belonging to every customer
- **date:** Purchase date of customer
- **price:** Amount spent for purchase by customer

---

### Libraries to install 

```
pip install -r requirements.txt
```

or pip install 
```
warnings
plotly
pandas
numpy
matplotlib
```

### Author

**Hasan Çatalgöl** -  [hasancatalgol](https://github.com/hasancatalgol)

---

### Acknowledgments:

```
MIUUL - VBO Data Science and Machine Learning Bootcamp and colleagues I worked with on a highly productive environment
www.veribilimiokulu.com
```


