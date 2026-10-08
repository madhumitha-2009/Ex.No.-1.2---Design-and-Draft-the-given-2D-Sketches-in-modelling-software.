# Design and Draft the given 2D Sketches in modelling software.

## Aim
To design and draft the given 2D mechanical component sketch using Autodesk Fusion modeling software. 

## System Requirements:
The software requires a computer setup meeting the following benchmark constraints: 
Operating System: Windows 11 / Windows 10 (64-bit) or macOS
Software Application: Autodesk Fusion (formerly Fusion 360)
Hardware (RAM): Minimum 8 GB (16 GB or higher recommended)
Graphics: Integrated or dedicated GPU with 1 GB VRAM minimum (2 GB recommended)
Internet Connectivity: Required for cloud operations (Minimum 2.5 Mbps download speed)  

## Procedure:
### Step 1: Create New Design and Set Units
Launch Autodesk Fusion and open a new design. Check the Document Settings and set the units to mm. Select Create Sketch and choose the XY Plane. The sketch environment with the origin is then displayed.
<img width="626" height="817" alt="image" src="https://github.com/user-attachments/assets/045ff4c1-5963-43fe-b86b-db5bcbb50dd6" />
 
### Step 2: Draw Reference/Construction Lines
Choose the Line Tool (L) and turn on Construction mode. Draw one vertical and one horizontal construction line through the origin (0,0). These reference lines are used to maintain symmetry and accurately locate the different features.
<img width="486" height="577" alt="image" src="https://github.com/user-attachments/assets/613df570-a3c5-4523-8f31-8814f7a10207" />

### Step 3: Construct the Main Hub and Internal Pattern
Turn off Construction mode and create the central concentric circles at the origin with R20 mm and R32 mm. Create the internal circular and radial features using the specified R16 mm and R21 mm dimensions. Create a circular pattern of 6 instances about the origin and trim the unwanted portions to obtain the required internal cutout arrangement.
<img width="607" height="366" alt="image" src="https://github.com/user-attachments/assets/29838e7f-0269-43a0-9457-91ebcb6bee26" />

### Step 4: Add the Main and Side Bosses
Create the six surrounding bosses as shown in the diagram. Draw concentric circles for the upper and lower bosses using R15 mm and R21 mm, and for the left and right side bosses using R15 mm and R20 mm. Position the bosses using the 60 mm vertical dimensions and the 20 mm and 50 mm horizontal dimensions shown in the drawing.
<img width="435" height="765" alt="image" src="https://github.com/user-attachments/assets/cb330512-e401-4e67-b8fd-3db804964f3e" />

### Step 5: Form the Outer Profile Using Arcs 
Create connecting arcs between the upper, side, and lower bosses using the specified radii shown in the diagram, including R15 mm, R20 mm, R21 mm, and R40 mm arcs. Apply tangent constraints between the arcs and the circular boss profiles to form the required outer boundary.
<img width="1028" height="498" alt="image" src="https://github.com/user-attachments/assets/3a1b7e76-21bd-4c05-9f93-23b2bdfd1a0f" />

### Step 6: Clean and Complete the Sketch 
Use the Trim Tool (T) to remove unnecessary portions of circles and arcs. Check the dimensions, alignment, symmetry, and tangent constraints. Ensure that the required outer profile, holes, and internal cutouts are correctly formed and closed, then select Finish Sketch.
<img width="650" height="282" alt="image" src="https://github.com/user-attachments/assets/c65c89b0-90c0-4b5f-a1eb-2617fff1bdb6" />

### Step 7: Extrude the Completed Profile 
Select Create → Extrude (E) and choose the required closed profile. Exclude the internal holes and cutouts from the selected region. Enter the required thickness, such as 10 mm, select New Body, and click OK to obtain the final 3D component.
<img width="525" height="542" alt="image" src="https://github.com/user-attachments/assets/fc09fc7d-f6ea-4f8d-8bf4-325e77265d35" />


## OUTPUT
<img width="1113" height="788" alt="image" src="https://github.com/user-attachments/assets/1567a461-55ec-4a83-8698-066626726f17" />

<img width="957" height="692" alt="Screenshot 2026-10-08 212653" src="https://github.com/user-attachments/assets/ef890847-2888-4da7-be73-2d8ba086c836" />

## RESULT
Thus the given sketch is drawn and drafted using fusion 360 tool. 

## MADHUMITHA.S 
## 26018117 
## 08.10.2026
