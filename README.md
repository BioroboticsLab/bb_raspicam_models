# Gravity Feeder 2026

## INTRODUCTION:

This repository contains 3D model files that are used in combination with the code in https://github.com/BioroboticsLab/bb_raspicam.
This feeder design is based on the reverse bottle feeder principle. It consists of 9 custom-designed 3D-printed parts:
1. **Tower**
2. **Lid Tower**
3. **Trough**
4. **Lid Trough**
5. **rBee (bottle lid adapter)**
6. **Scale Socket**
7. **Cam Holder**
8. **Connection Tower-Trough**
9. **rBee Containment**

In addition to these printed components, the assembly integrates off-the-shelf electronic hardware that is not part of the design files but required for full functionality:
1. **Raspberry Pi 4 (microcontroller)**
2. **Load cell scale (weight sensor)**
3. **Camera module**

The 3D-printable parts are available as STL files in this branch of the repository. The final setup is also provided as an assembly file. All fastened connections use **M2.5 screws**.

---

## PART DESCRIPTION:
<br><br><br>
<img align="right" style="margin-right: 50px;" width="316" height="338" alt="Bildschirmfoto 2026-03-24 um 12 01 30" src="https://github.com/user-attachments/assets/95881716-8863-4388-aee7-a3abc20c590b" />

### Tower:

The tower houses the **Raspberry Pi** and supports the **camera module**.
* The **cam holder** mounts to the top via screws, positioning the camera for a clear view of the trough.
* The **Raspberry Pi** is screwed to the inside of the tower and protected by the lid, which fits over the assembly.
* At the base, the **connection piece** attaches via screws and provides a sliding connection to the trough.

<br><br><br><br>

<img align="right" style="margin-right: 50px;" width="180" height="220" alt="Bildschirmfoto 2026-03-24 um 12 09 11" src="https://github.com/user-attachments/assets/fd737866-644e-4541-97c0-60a95bc8e931" />

<br>

### Lid tower:
The lid slides onto the back of the tower, protecting both the **Raspberry Pi** and the **camera module**.

<br><br><br><br><br><br>

<img align="right" style="margin-right: 50px;" width="348" height="285" alt="Bildschirmfoto 2026-03-24 um 12 18 47" src="https://github.com/user-attachments/assets/3a8ba56b-83b5-40d3-8c55-e4d1c9f9becd" />

<br>

### Trough:

The trough sits beneath the camera and connects to the tower via a sliding mechanism.
* The **scale containment** can be plugged onto it.
* It features a **lowered drinking pool**, which is covered by the lid trough, with the recessed design providing passive overflow protection.
* Both the **trough** and the **rBee** have a **male tube connector**, with the supply tube secured on both ends using **hose clamps**.

<br><br><br><br>

<img align="right" style="margin-right: 50px;" width="326" height="150" alt="Bildschirmfoto 2026-03-24 um 12 26 16" src="https://github.com/user-attachments/assets/3fcf2aa6-34dd-404c-afce-c65f6d167740" />


### Lid Trough:
The lid sits over the drinking pool to make it easier for bees to drink. Small ridges inside the trough form a **snap-fit connection**, keeping the lid in place and preventing it from floating.

<br><br><br>

<img align="right" style="margin-right: 50px;" width="270" height="291" alt="Bildschirmfoto 2026-03-24 um 12 38 14" src="https://github.com/user-attachments/assets/09e276f3-db55-4d00-9351-b7ed90f33d0d" />


### rBee:

The **rBee** screws onto the bottle neck.
* When fully tightened, it **seals the bottle** and prevents water from flowing, allowing to be transported horizontally.
* A small **vent** integrated into the thread provides an air connection to the bottle neck, enabling the reverse bottle feeder principle to function.
* Once connected to the trough, the **water level** is determined by how far the bottle is screwed into the rBee, as this controls the height of the bottle neck.
* The **ridges** on the outside of the rBee allow the bottle to be loosened by hand once mounted, using the **tilt guard** integrated into the scale socket as a counterhold.

<br><br><br>

<img align="right" style="margin-right: 50px;" width="233" height="285" alt="Bildschirmfoto 2026-03-24 um 12 45 30" src="https://github.com/user-attachments/assets/e1751ef0-57f5-496b-9f0e-2821e01ce108" />

 <br><br>

### Scale Socket:

The **scale containment** houses the scale. It connects to the trough via a sliding connection and serves two additional functions: a **tilt guard** that stabilizes the bottle, and a **counterhold** that allows the bottle to be screwed into the rBee after the assembly is fully connected.

<br><br><br><br>

<img align="right" style="margin-right: 50px;" width="170" height="140" alt="Bildschirmfoto 2026-03-24 um 13 57 54" src="https://github.com/user-attachments/assets/ae06450c-809e-44ca-bd60-99f299202f16" />

### Cam Holder:
The **cam holder** contains the cam and is screwed on at the top of the tower.

<br><br><br>

<img align="right" style="margin-right: 50px;" width="282" height="121" alt="Bildschirmfoto 2026-03-24 um 14 00 06" src="https://github.com/user-attachments/assets/068b0a80-1888-4617-9c09-311fd46d4277" />


### Connection Tower-Trough:
This piece is screwed on at the bottom of the tower and enables sliding the trough on the tower.

<br><br><br>

<img align="right" style="margin-right: 50px;" width="141" height="214" alt="Bildschirmfoto 2026-03-24 um 14 04 06" src="https://github.com/user-attachments/assets/174998e2-90c2-49a1-a9b9-164b597a293b" />


### rBee Containment:

This piece screws onto the scale and creates a platform for the **rBee**.

<br><br>
---

## ADDITIONAL HARDWARE:

* **M5Stack Scale:** The M5Stack Scale Unit is a compact weighing module that uses an **HX711 24-bit A/D converter** to measure loads up to **5kg**. It connects via a **Grove interface**, enabling the bee feeder to track syrup consumption by monitoring weight fluctuations.
* **RaspberryPi 4:** The Raspberry Pi 4 serves as the central hub for the bee feeder, providing the processing power and connectivity needed to handle **data logging** and **wireless communication**. It is strongly advised to use the **official Raspberry Pi 4 power supply**.
* **Hose Clamps:** These single-wire spring hose clamps are made of **zinc-plated manganese steel** and provide a constant tension seal to prevent leaks.
* **Tube:** Any aquarium tube will do. Make sure your tube has an **inner diameter of 3 mm**.

---

## ASSEMBLY INSTRUCTIONS



**Before you start:** Print all 9 parts. Have **M2.5 screws**, an **M5Stack scale**, a **Raspberry Pi 4**, a **camera module**, a **supply tube**, and **hose clamps** ready.

<img align="right" style="margin-right: 50px;" width="228" height="302" alt="Bildschirmfoto 2026-03-25 um 13 35 07" src="https://github.com/user-attachments/assets/8fc35003-950f-4fcd-8fa9-912295c10053" />

<br>

### 1. Prepare the tower       

1. Screw the **Connection Tower-Trough** onto the base of the tower (**M2.5 screws**).
2. Screw the **Cam Holder** onto the top of the tower (**M2.5 screws**).
3. Screw the **camera module** into the Cam Holder.
4. Screw the **Raspberry Pi** to the inside of the tower.
5. Connect the **camera module** to the Raspberry Pi via the camera cable.
6. Connect the **scale** to the Raspberry Pi.
7. Slide the **Lid Tower** onto the back of the tower.

### 2. Prepare the scale assembly
1. Screw the **rBee Containment** onto the top of the scale.
2. Place the **scale** into the bottom of the **Scale Socket**.

### 3. Connect the trough
1. Slide the **trough** onto the Connection Tower-Trough until the end.
2. Slide the **Scale Socket** onto the trough using the connector on the side of the trough.

### 4. Add the tube and lid
1. Attach the **supply tube** to the male connector on the trough using a **hose clamp**.
2. Place the **Lid Trough** into the drinking pool until it **snaps into place**.

### 5. Mount the bottle
1. Fill the bottle and screw the **rBee** all the way onto the bottle neck to seal it.
2. Turn the bottle upside down and place it into the **rBee Containment**.
3. Attach the **supply tube** to the male connector on the rBee using a **hose clamp**.

### 6. Start the feeder
1. Plug the **power cable** into the Raspberry Pi.
2. Start your **scale logger** and **camera recordings** on the Raspberry Pi.
3. **Unscrew the bottle slightly** from the rBee using the counterhold of the Scale Socket to allow water to flow into the trough.
4. The **water level** is controlled by how far the bottle is unscrewed.


