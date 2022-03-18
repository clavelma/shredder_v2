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
    
   * FR1:  The shredder needs to work on a standard 220V 50Hz EU plug
   * FR2:  The shredder needs to respect the 1m50x1mx1m50 maximum volume
   * FR3:  The shredder needs to shred plastic into chips with a surface inferior to 1cm²
   * FR4:  The shredder needs to stop in case of emergency in less than 3 seconds
   * FR5:  The shredder must be secured to prevent injury on contact (against moving parts and projectiles)
   * FR6:  The shredder needs to have a power-on and/or operation indication that the operator can see
   * FR7:  The shredder must not exceed the maximum accepted noise level
   * FR8:  The shredder should not transform one of the labs and fablabs of the RAFU network into a storage place for all the plastic chips.
   * FR9:  The shredder needs to have a reverse function in case of blocking or any other mechanical problem
   * FR10: The shredder and its installation should be stable and strong.
#The effects of vibration can be severe. Unchecked vibration can accelerate rates of wear (e.g., reduce bearing life) and damage equipment. Vibrating machinery can create noise, cause safety problems and lead to degradation in plant working conditions.
