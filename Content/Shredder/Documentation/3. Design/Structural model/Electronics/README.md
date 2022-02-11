## **How to document a structural model of electrical products?**

 ### **1. Architectural structure**
<details>
  <summary>Click to see the guideline!</summary>
 
- **Definition:** *The architectural structure is a physical or logical layout of the components of a system design and their internal and external connections.*

 ```
 1. What minimum documentation should the architectural structure provide?

    - A model specifying the kind of components and their sub-components in the format of a tree  or a graph including
      - DC motor
      - A/D converter
      - DC converters  
      - Rotor
      - Sensor system
      - Motherboard
      - kit
      - Resistor
      - Transistors
      - IC
      - Sensors
      - Etc.

2. How to implement the architectural model?

  - Use modeling language for representation, such as
    - SysML (Block Definition, Activity, or Internal Block diagram)
    - UML
  - Use open-source software for modeling the tree or graph representation, such as
    - Papyrus
    - Modelio
    - Capella 
  ```
</details>

<details>
  <summary>Click to see the examples!</summary>
 
*The links below show some kinds of the architectural structure of the electrical product.*

#### *Example 1: Architectural structure of* [PX4 Vision](https://wikifactory.com/+holybro/px4-vision) 

 ![Image of architectural structure of PX4 Vision](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Architecture%20of%20electrical%20structural%20model.jpg)

<a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FArchitecture%20of%20electrical%20structural%20model.drawio" target="_blank">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FArchitecture%20of%20electrical%20model.png">Edit in diagrams.net</a>

#### *Example 2: Architectural structure of* [Open-Source-Ventilator](https://github.com/ermtl/Open-Source-Ventilator/blob/master/hardware/datasheets/A4988.pdf)

 ![Image of Structural graph of Open-Source-Ventilator](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Architectural%20stracture%20of%20open%20source%20ventilator.png)

#### *Example 3: Architectural structure of* [ GlasVent emergency ventilator](https://onlinelibrary.wiley.com/doi/10.1002/gch2.202000046) (refer to figure 6 of the link)
</details>

### Template of architectural structure
 
  #### Architectural structure documentation
  1. A model specifying of components
 
   ![Image of template for architectural structure](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Architectural%20structure%20for%20template.jpg)
 
*You can use the link below to define the architectural structure of your project/product.*
 
  <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FArchitectural%20model%20of%20mechanical%20structure%20for%20template.drawio" target="_blank">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2F%20Architectural%20model%20of%20mechanical%20structure%20for%20template.png" target="_blank">Edit in diagrams.net</a>
 
  2. Name of modeling language
     * UML
     * ...
  3. Name of software
     * Online app diagram
     * ...
 
### **2. Modelling a electrical design in an editable file format**
<details>
  <summary>Click to see the guideline!</summary>
 
- **Definition:** *An editable file format is a standard way that information is encoded for storage and allows the makers to study, modify the layout of the circuit diagram, Printed Circuit Board (PCB), and Schematic diagram.* 

 ```
To reuse a electrical design, it should provide information consist of:

 1. Preferable file format
   - Editable file formats that could be:
     - Source formats such as .gbr, .lib format   
     - Neutral formats such as Kicad_mod, kicad_pcb
 2. Preferable open-source software 
   - Tiny CAD
   - KiCAD
   - ADINA
  ```
 </details> 

<details>
  <summary>Click to see the examples!</summary>
 
#### *Example of an editable design file formats:* 

*1. [Nasa-JPL, source files](https://github.com/nasa-jpl/open-source-rover/tree/master/electrical/pcb/arduino_uno_sheild/gerbers/rev_b)*

*2. [AmbovVent, Neutral files ](https://github.com/AmboVent-1690-108/AmboVent/tree/master/1-Electronics)*
</details> 

### Template of file formats
 
 #### Documentation a design in an editable file format
  1. Editable file formats
     * Source formats
     * Neutral formats
  2. Name of software
     * Tiny CAD
     * ...
 

