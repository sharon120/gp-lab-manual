# EXP-01: Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.
## Date: 05/03/25
## Aim:
To implement various effects in a material such as emissive, roughness and metallic
properties in Unreal Engine.

## Procedure:
**1. Open Unreal Engine:**
* Launch Unreal Engine and create a new project or open an existing project.
  
**2. Create a New Material:**
* In the Content Browser, right-click and select ‘Material’ to create a new material.
* Name it appropriately (e.g., ‘M_EffectMaterial’).
  
**3. Adjust the Emissive Property:**
* Open the material by double-clicking on it.
* In the Material Editor, use a Constant3Vector node to define a color for the emissive effect.
* Connect the node to the Emissive Color input of the Material node.
* Adjust the color's brightness by multiplying it with a constant to simulate glowing material.
  
**4. Modify the Roughness:**
* Use a Scalar Parameter node to control the roughness (0 for smooth, 1 for rough).
* Connect this node to the Roughness input of the material node.
  
**5. Control Metallic Property:**
* Use another Scalar Parameter node to define metallicity (0 for non￾metallic, 1 for metallic).
* Connect the scalar to the Metallic input of the material node.
  
**6. Apply the Material to a 3D Model:**
* Drag and drop the material onto a 3D model in the scene to see the effects in real-time.
  
**7. Tweak the Values:**
* Experiment with different values for emissive color, roughness, and metallic properties to see how they affect the appearance of the material.
  
**8. Take Screenshots:**
* Capture the visual results using the Screenshot tool within Unreal Engine

## Output:
### 1. Emissive property (glowing material):
![image](https://github.com/user-attachments/assets/2c4ffcb2-c8b2-4c8e-827b-a3daa38286f1)

### 2. Roughness property (matte vs shiny surfaces):
![image](https://github.com/user-attachments/assets/8ba9d5f9-b604-4256-8541-9994367c0be0)

### 3. Metallic property (metallic vs non-metallic appearance):
![image](https://github.com/user-attachments/assets/8461e700-0ac1-4e17-a4e8-91dd9a731a82)

### 4. Final Output:
![image](https://github.com/user-attachments/assets/0ea17acd-c149-416f-85f3-a6b2e39ad54f)

## Result:
Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine was done successfully.
