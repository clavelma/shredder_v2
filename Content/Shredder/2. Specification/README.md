# **Specification**

*The specification consists in describing the product with a "black box" external view to capture the intermediate technical objects (stakeholders, external interfaces, services, and constraints) that serve to, *in fine*, elucidate the product requirements.*

## **How to document the specifications?** 
  
## **1. Stakeholders:**

![stakeholders_shredder drawio](https://user-images.githubusercontent.com/95290174/152964940-641c68a4-78e5-4441-ad8c-f626bcd7d0b1.png)

  
## **2. External interfaces**

*The image below shows the external interfaces of  ADD-ONS of XYZ cargo as a graph*

![Image of External interfaces of XYZ cargo-ADD ONS](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Sources/Images/External%20interfaces%20of%20XYZ%20Cargo%20ADD-ONS.jpg)

<a href="https://app.diagrams.net/?libs=general#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FExternal%20interfaces.drawio">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FExternal%20interfaces.png">Edit in diagrams.net</a>
</details>

### Template of external interfaces
   
   * Clients
       * needs
   * Users
       * use
       * repair
   * Partners
       * data
       * technical support
   * Media
       * reproduce
       * data
   * European standards
       * laws
       * norms
       * security
   * Environment
       * supply
       * adapt
       * reuse
       * technical support
  
 ![Image of stakeholder diagram for template](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Sources/Images/External%20interfaces%20for%20template.jpg)
  
   *The link below can be used to define the external interfaces of your project/product.*
  
  <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FExternal%20interfaces%20for%20template.drawio">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FExternal%20interfaces%20for%20template.drawio">Edit in diagrams.net</a>

## 3. Service *(synonyms: external function, capability)* 
<details>
  <summary>Click to see the guideline!</summary>
  
- **Definition:** *A service is an effect intended by a stakeholder resulting from the interaction of the product with its environment (i.e. what the  product is for).*

- **Comments:**
  - *Services provide users with an exchange value that can be included in an economic system (e.g. airlines buy flight hours).*
  - *Services are intended effects that can be observed from outside the product ("black box" external view), but not from outside an internal component ("white box" internal view).*
  - *Services are defined in a solution neutral-way.*
  - *Services can be stated as follows: The [Product] shall enable [Stakeholder] [Action verb] (e.g. The product shall enable end-user to clean its teeth)*
  - *we often reason in terms of action verbs to communicate expected behaviors, so it would be nice to be able to search designs with action verbs*
</details>

<details>
  <summary>Click to see the example!</summary>
  
 ```
  What does contain the minimum documentation of the service to stakeholders?
  
  Example of services for ADD-ONS of XYZ Cargo
  
    - The ADD-ONS shall enable the food producer to store food
      - 1.1 solid (10 kilos)
      - 1.2 liquid (5 litrs)
    - The ADD-ONS shall enable the food producer to heat food
      -  2.1solid (150 deg Celcius)
      - 2.2 liquid (80 deg Celcius)
    - The ADD-ONS shall enable the food producer to cool down food for 4 hours
      - 3.1 solid (6 deg Celcius)
      - 3.2 liquid (6 deg Celcius)
      
    - ...
  ```
 </details>

### Template of services
  
   * Services to clients
       * The shredder shall enable the ABS&PLA plastic from 3D printing scraps to be reduce into medium or small chips.
       * The shredder shall enable the thermoformable plastic from thermoformable plastic plate scraps to be reduce into medium or small chips.
   * Services to users
       * The shredder shall enable the plastic from user's personal collection to be reduce into medium or small chips.
   * Services to partners
       * The shredder shall enable the plastic from partner's personal collect to be reduce into medium or small chips.
   * Services to media
       * The shredder will serve as a functional example of low tech solution for plastic recycling.
   * Services to european standards
       * The shredder will meet the safety and working standard conditions based on european standards. 
   * Services to environment
       * The shredder in all ramifications, will be safe to use and environmental friendly.

## 4. Constraint *(Synonyms: non function requirement)*

### Template of constraints
  
   * The shredder should be dismantled for recycling purposes
   * The shredder should be realise and operate in a low tech philosophy
   * The shredder should follow the european standards
   * Open source community should be able to reproduce it
   * User should be able to use it in security
   * Ginova should be able to handle the maintenance
   * The shredder should be incorporating in Ginova
   * The shredder should be able to shred the plastic from the collect
   * The shredder should be built using the maximum of the existing prototype
   * The shredder assembly and user should be accessible and open source
   * The shredder should be realised thanks to the RAFU network facility
   * The shredder should be able to go forward and to go backward
     
  
## **5. Requirement**
 
 ### Template of requirements
    
   * FR1: The compactor needs to work on a standard 220V 50Hz EU plug
   * FR2: The compactor needs to be able to melt PLA (175°C)
   * FR3: The compactor needs to compact plastic plates with a thickness of 1.6, 2.5 and 3.2 mm
   * FR4: The compactor needs to filter the toxic air
   * FR5: The compactor needs to be isolated
   * FR6: The compactor needs to be safe for the operator (heat)
   * FR7: The compactor needs to have a power-on and/or operation indication that the operator can see
   * FR8: The compactor should have a thermometer (to set the temperature)
