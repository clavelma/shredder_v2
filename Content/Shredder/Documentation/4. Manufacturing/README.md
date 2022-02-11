# **Manufacturing**

*I would like to enable makers to understand the process by which raw materials transform into a final product.*

## **How to document a manufacturing process?**

*Manufacturing instructions can guide the makers to follow a process for replicating a product. Manufacturing instructions mean full description and instructions concerning raw material, operating conditions, and process to be employed for the manufacture and assembly of the product.
The bill of material (BOM) is the document that describes all the components and their references. If the component is to be purchased one should find all the information required to buy the part. If the part is to be manufactured one should find all the descriptions of the manufacturing instructions as described below.* 

## **How to document a manufacturing process part?**

*If the part is to be manufactured one should find all the descriptions of the manufacturing instructions as described below.* 

### *1. Bill of material (BOM)*
<details>
  <summary>Click to see the guideline</summary>
 
 - **Definition:** *A bill of materials (BOM) is a comprehensive list of parts, items, and other materials required to create a product, as well as instructions required for gathering and using the required materials.*

```
What should include the bill of material (not limited to...)?

   1. Part number
   2. Item name
   3. Manufacturer part number
   4. Digi-Key part number
   5. Description
   6. Manufactured part (link to manufacturing instruction)
   7. Purchased part (link to seller website)
   8. Quantity
   9. Price
   10. Manufacturing standard lead time
   11. Packaging
   12. BOM notes
   13. ...
   ```
</details>

<details>
  <summary>Click to see the example</summary>
 
 #### *Example 1: [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/bill_of_materials)*
  
![image](https://user-images.githubusercontent.com/59058909/126754681-8afeaaa9-619e-49c5-94ca-962bd0d225c3.png)

*BOM of JPL open-source Rover*
  
 #### *Example 2: [SatNOGS Rotator v3](https://gitlab.com/librespacefoundation/satnogs/satnogs-rotator/blob/master/rotator-bom.ods)*
  
 #### *Example 3: [Krab v1.0](https://projects.fablabs.io/@avishek/krab-v10)*

</details>

### BOM Template

 #### Bill of material
 
 *You can use this template on the App diagram to define the bill of material of your project/product.*

![image of BOM](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/BOM%20template-2.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FBOM%20template.drawio" target="_blank">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FBOM%20template%20of%20manufactured%20workpiece.png">Edit in diagrams.net</a>
 
  ### *2. Manufacturing instructions should include:*
 
 #### *2.1. Manufacturing tools*
  <details>
  <summary>Click to see the guideline!</summary>
 
  - **Definition:** *It means all the machinery, equipment, and processes used to manufacture products. Manufacturing technology guide to find the type of necessary technology to produce the part. In that case, it should describe the most suitable technology according to the context.*

 ```
 What should include the documentation of manufacturing tools?
 
 Type of machines used 

   1. CNC machine tools for machining metal or other rigid materials
     - Milling 
     - Lathe
     - Cutting 
     - Drilling 
     - Etc.
    
   2. Other common manufacturing tools
     - 3D printing (FDM, SLS...) 
     - Thermoforming
     - Burning machining technology (laser cutting, Plasma cutting, ...) 
     - Bonding technologies (Solder, cold welding, arc welding, adhesive bonding ...)  
  
   3. Finishing: to achieve the right properties such as surface quality, geometrical accuracy, and mechanical properties, finishing is essential. 
     - Sanding after 3D printing
     - Gap filling
     - Blasting
     - Polishing
     - Priming and painting
     - Etc.
  
 How to visualize the manufacturing tools? 
  1. Images 
  2. Videos  
 ```
 </details>
 
  <details>
  <summary>Click to see the examples!</summary>
 
   #### *Example 1:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/mechanical/body_assembly#3-machiningfabrication)
   
   #### *Example 2:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Build_Sequence) 
  </details>
 
   #### Template of Manufacturing tools
   
*You can use this template on the App diagram to define manufacturing tools.*
 
![image of Manufacturing tools](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Manufacturing%20tools.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FManufacturing%20technology.drawio">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FManufacturing%20technology.png">Edit in diagrams.net</a>

 #### *2.2. Manufacturing sequences and instructions*
 <details>
  <summary>Click to see the guideline!</summary>
 
  - **Definition:** *Manufacturing sequences refer to step-by-step machining and manufacturing processes in a target-oriented arrangement to enable manufacturing.*
  
  - **Comments:**
  
      * The machining sequence should define for the manufacturing of each part.
      * Process parameters are all those parameters that are inherent to any machining operation and should have a suitable finite value to smooth and efficient removal of materials.
      * Manufacturing standard file formats support some of the manufacturing processes and the surface geometry of a design without the possibility of modification.

```
What does include the documentation of manufacturing sequences and instructions?
 
  1. Name of the related machine of each step
  2. Describing step by step sequence of the machining process
    - Machine
    - Type of operation
    - Tools description 
    - Process parameters of each machining operation ( refer to the template of manufacturing sequences below)
       - Process parameters of 3D printing
       - Process parameters of Laser cutting
       - Process parameters of CNC machines such as Lathe, Milling, etc.
       - Process parameters of arc welding
    - Raw material
    - Manufacturing files (STL, SVG or G-code, ...)
       - CAD files in an interchange format such as STL that is suitable for 3D printing 
       - Nominal geometry and its allowable variation by using symbolic language on 2D drawings like SVG, JPEG, and PDF format that is suitable for laser cutting
       - Manufacturing export formats such as G-code, STEP-NC is suitable for CNC machining
       - Circuit board design formats such as Gerber RS-274X, excellon that is suitable for vector photoplotters 2D mechanical NC machines
  ``` 
</details>

 <details>
  <summary>Click to see the examples!</summary>
 
   #### *Example 1:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/mechanical/body_assembly#3-machiningfabrication)
  
   #### *Example 2:* [DIY Dremel CNC design and parts](https://www.thingiverse.com/thing:3004773) and [its CAM file for machining](https://www.estlcam.de/) 
  
   #### *Example 3:* This table shows an example of the manufacturing sequences.
  
  ![image of machining sequences](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Example%20of%20machining%20sequences.jpg)
  
  #### *Example 4:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Specifications), [2D drawing file](https://wiki.satnogs.org/File:C1001.png)
  
  #### *Example 5:* Types of CAD format of [transmagic](https://transmagic.com/cad-formats/)
   </details>
  
  #### Template of manufacturing sequences
  
   *You can use these parameters for each machining operation to complete the manufacturing sequences on the App diagram.*
  
  #### 1. 3D printer parameters 

   * Extruder setting 
      * Extrusion multiplier
      * Retraction distance 
      * Retraction speed 
      * Coasting
   * Layer setting
      * First layer height
      * First layer speed
   * Laver height
   * Printing bed temperature
   * Infill setting
      * Internal/Eternal fill pattern
   * Temperature setting
   * Cooling setting
     
  #### 2. CNC machines parameters such as Lathe, Milling, etc. 
  
   * Cutting parameters
      * Cutting speed
      * Feed rate
      * Cutting depth
      * Cutting width
      * Cutting force
      * Spindle speed
      * Cutting temperature
   * Cutting tool
      * Tool Geometry
      * Tool setting
   * Coolant 
      
 #### 3. Burning machining parameters such as laser cutting 
  
   * Beam parameters
      * Wavelength
      * Power and intensity 
      * Polarization
   * Process Parameters
      * Focusing of laser beams (the focal length of the lens)
      * Focal position
      * Angle of incidence
      * Cutting speed
      * Gas pressure
      * Stand-off distance
      * Expected duration

  #### 4. Bonding technologies parameters such as Arc welding
    
   * Welding current
   * Welding voltage
   * Arc travel speed
   * Torch angle
      * Longitudinal
      * Transverse
   * Electrode force
   * Electrode diameters
   * Length of arc
   
![image of manufacturing sequence](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Manufacturing%20sequences%201.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FMachining%20parameters.drawio">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2Fmachnining%20paramters.png">Edit in diagrams.net</a>
 
 

