# Analog_ic_design_project

# Internally Compensated LDO

## Low Load(2ma)

### Case-1: Loop gain analysis:-

**Schematic**

![Screenshot 2024-12-03 215715](https://github.com/user-attachments/assets/fee7a096-3ef0-4455-93e6-fe4644fbe93d)

**Explanation of the artifact used:-**

**Output log file:-**
![image](https://github.com/user-attachments/assets/fe15a521-710d-4b12-8d1d-5b0adb58d749)


# Transistor Operating Regions Table

This document provides a table summarizing the operating regions of several transistors based on their parameters.

## Table:

| **Transistor** | **Type** | **Vds (V)** | **Vgs/Vsg (V)** | **Vt (V)** | **Vgs/Vsg - Vt (V)** | **Operating Region**   |
|----------------|----------|-------------|------------------|------------|-----------------------|------------------------|
| M1            | PMOS     | 0.652       | 0.652           | 0.489      | 0.163                | Saturation             |
| M2            | PMOS     | 0.522       | 0.652           | 0.490      | 0.162                | Saturation             |
| M3            | PMOS     | 0.364       | 0.522            | 0.481      | 0.041                | Saturation             |
| M4            | NMOS     | 0.734       | 0.734           | 0.467        | 0.267                | Saturation             |
| M5            | NMOS     | 0.485       | 0.607           | 0.468      | 0.139                | Saturation             |
| M6            | NMOS     | 0.355       | 0.609           | 0.468      | 0.141                | Saturation             |
| M7            | NMOS     | 0.393       | 0.734           | 0.468      | 0.266                | Saturation             |
| M8            | NMOS     | 1.04        | 0.734           | 0.466      | 0.268                | Saturation             |








### Output on Python:-

![image](https://github.com/user-attachments/assets/59d290cc-2641-4349-8903-37ea35e7dffb)


### Phase margin

![Screenshot 2024-12-03 215638](https://github.com/user-attachments/assets/d2b6bc1d-3ad0-491b-87d3-3b8aa7483429)


## Case 2:- Open Loop PSRR calculation

### Schematic

![image](https://github.com/user-attachments/assets/db534bfc-6962-404b-a3ac-95dc34842b4c)


### Explanation of the artifact

### Python plots


## Case 3:- Closed Loop PSRR Calculation

### Schematic

![image](https://github.com/user-attachments/assets/3af5bdd6-786e-43df-8d68-c779ad49a757)

### Explanation of the artifact

### Python plots

### Hand Calculations vs Simulation Results


# For heavy load ( 10 ma )

## Case 1:- Loop gain analysis:-

### Schematic

![Screenshot 2024-12-03 215850](https://github.com/user-attachments/assets/ef1ab793-0dc1-4552-bfd4-999130da643c)


### Python plots

![image](https://github.com/user-attachments/assets/9da2dfa9-82bd-4dce-8acd-4f49614c0e35)


### Phase margin

![Screenshot 2024-12-03 215830](https://github.com/user-attachments/assets/b3944f33-0b71-4fd6-9b2e-25f150c0f6ff)


### Spice Output Log

![image](https://github.com/user-attachments/assets/9d00a5a7-42af-46dc-b791-85d6535928f8)


# Transistor Operating Regions Table

This document provides a table summarizing the operating regions of several transistors based on their parameters.

## Table:

| **Transistor** | **Type** | **Vds (V)** | **Vgs/Vsg (V)** | **Vt (V)** | **Vgs/Vsg - Vt (V)** | **Operating Region**   |
|----------------|----------|-------------|------------------|------------|-----------------------|------------------------|
| M1            | PMOS     | 0.651       | 0.651           | 0.489      | 0.162                | Saturation             |
| M2            | PMOS     | 0.64        | 0.651           | 0.489      | 0.162                | Saturation             |
| M3            | PMOS     | 0.367       | 0.64            | 0.481      | 0.159                | Saturation             |
| M4            | NMOS     | 0.734       | 0.734           | 0.467        | 0.267                | Saturation             |
| M5            | NMOS     | 0.368       | 0.609           | 0.468      | 0.141                | Saturation             |
| M6            | NMOS     | 0.358       | 0.609           | 0.468      | 0.141                | Saturation             |
| M7            | NMOS     | 0.391       | 0.734           | 0.468      | 0.266                | Saturation             |
| M8            | NMOS     | 1.03        | 0.734           | 0.466      | 0.268                | Saturation             |



## Case 2:- Open Loop PSRR calculation

### Schematic

![image](https://github.com/user-attachments/assets/ec1025c3-24ea-4bee-8f06-04e198f5c7e2)


### Python plots

## Case 3:- Closed loop PSRR calculation

### Schematic

![image](https://github.com/user-attachments/assets/112705cf-8831-4b34-a88a-96ed6861a41c)

### Python plots

## Transient Analysis

### Schematic

![image](https://github.com/user-attachments/assets/f58b0da4-1fec-4ac7-bac4-430dd49bf492)



### Ltspice Output:-
![image](https://github.com/user-attachments/assets/c3b5884f-3f67-4d78-a7ab-df21042d98df)

### Python Plots:-















