# **Functional model**

***I would like to** to enble makers to understand what the product and its parts are for.* 

## **What is a functional model?**

* A description of the functions performed by a product.
* An opportunity to break down a product into smaller pieces that can be more easily understood.
* At the highest level of a functional breakdown (black box view), service functions are the effects (intended by its stakeholders) of the interaction of the product with its environment.([Specification](https://github.com/OPEN-NEXT/wp2.3_template/tree/main/Documentation/2.%20Specification#specification))
* At the intermediate and lowest levels of a functional breakdown (white box view), technical functions are input-output relationships transforming matter, energy or information flows. They are expressing in a non-solution neutral way and observable from inside the product. A set of technical function is necessary for the realization of a service function.

## **Why should you define functional model?**

* A functional model helps to break down a complicated problem into simple sub-problems.
* A functional model helps to anticipate failures occurring when an intended effect of the product is no longer produced on its environment.
* A function is the main input to derive the functional requirements required to define the conditions of use of the product as well as to provide objective evidences through the validation and verification activities. 

## **How to document a functional model?**

*The documentation of technical functions, which requires adopting an internal (white box) viewpoint on the product, consists in breaking down the service function into sub-functions. The decomposition process is no more solution neutral as it requires to make a decision at every indenture level. The functional decomposition requires two modelling approaches: function tree and functional graph.*

 ### **1. Functional tree**

*What are the top-down decomposition of a service function that helps to simplify the problem to solve?* 

- **Definition:** *The functional tree is a top-down decomposition of function into sub-functions that helps to simplify the problem to solve.*

- **Comments:**

  - *A top-down and bottom up reading of the functional tree provides insight on the “how” and “why”, respectively.*
  - *The decomposition process should be stopped when technical function is sufficiently detailed to reuse, make, or buy a design solution.*

  ```
  Metadata:
  
  - 
  ```

### **2. Functional graph**

*What is the multi-level logical articulations of technical functions as input-output relationships transforming flows?* 

- **Definition:** *The functional graph is a multi-level logical articulation of technical functions.*

- **Comments:**

  - *Relationships between functions are in/out-going flows of matter, energy or information.*
  - *Logical AND/OR gates can be used to define concurrent or sequential functions.*

  ```
  Metadata:
  
  - 
  ```

### **3. Functional modelling language**
*What is the functional modelling language to express the structure of functional model?* 

```
  Metadata:
  
  - UML (Use Case diagram)
  - SysML (Block Definition, Activity, or Internal Block diagram)
  - SADT/IDEF0 
  - Functional flow block diagram.
 
  ```
  
  ### **4. Functional modelling environment**
*What is the open-source functional modelling environment?* 

```
  Metadata:
  
  - Papyrus
  - Modelio
  - Capella
  - etc.
  ```
