# DESIGN-OF-INVERTING-AMPLIFIER-NON INVERTING-AMPLIFIER-DIFFERENTIAL AMPLIFIER-USING-OP-AMP-741
# AIM:
To design and construct a inverting, non- inverting and differential amplifiers.

# APPARATUS REQUIRED:
<img width="944" height="253" alt="image" src="https://github.com/user-attachments/assets/75606ec6-5b9a-4a89-a137-c0ab7d2100ff" />


# THEORY:
Op-amp in open-loop configuration has a very few application because of its enormous open- loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1. Inverting amplifier.
2. Non-inverting amplifier.
3. Differential amplifier.
The entire configuration can be operated with either AC or DC input.

# INVERTING AMPLIFIER:
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

# NON - INVERTING AMPLIFIER:
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

# DIFFERENTIAL AMPLIFIER
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
AV=Vd/V2-V1=-Rf/Ri

# PROCEDURE:
1. Select R1 as a constant value and choose a value of Rf.
2. Connect the circuit as per as the circuit diagram.
3. Apply the constant amplitude input voltage to the circuit.
4. Measure the output voltage amplitude for different value of V1 from DSO.
5. Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6. Practical gain & theoretical voltage should be approximately equal.
7. Plot the graph of the input wave versus output wave for any one practical case.
   
# PIN DIAGRAM
<img width="401" height="173" alt="image" src="https://github.com/user-attachments/assets/84328324-1ceb-4c3c-98af-eb5f5e1b7829" />

# CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
<img width="597" height="277" alt="image" src="https://github.com/user-attachments/assets/a0babb36-f3b8-4467-b8e0-8af9caed8ee1" />

# MODEL GRAPH:
<img width="450" height="228" alt="image" src="https://github.com/user-attachments/assets/235f4402-0bee-42b7-80de-38055bb37b2c" />

# CIRCUIT DIAGRAM:
# NON-INVERTING AMPLIFIER:
<img width="451" height="254" alt="image" src="https://github.com/user-attachments/assets/a13892d7-98ac-47f5-a46d-0ec4474ed449" />

# MODEL GRAPH:
# NON-INVERTING AMPLIFIER
<img width="421" height="217" alt="image" src="https://github.com/user-attachments/assets/acb72459-bb16-44df-9cb8-b8bbfb5213fe" />

# CIRCUIT DIAGRAM: DIFFERENTIAL AMPLIFIER
<img width="453" height="335" alt="image" src="https://github.com/user-attachments/assets/9de2e6f0-5af0-444c-8c7f-25ee4b922fa4" />

# MODEL GRAPH:
<img width="658" height="213" alt="image" src="https://github.com/user-attachments/assets/a41aaf0b-11ac-4694-9366-34c0028075c3" />

# DESIGN:
Inverting amplifier:
A = -Rf/R1 
Take A = 10 
Rf = 10 R1 
Choose R1 = 1 kΩ, Rf = 10 kΩ 

Non inverting amplifier:
A = 1 + Rf/R1 
Take A = 2 
Rf = R1 
Choose Rf = 10 kΩ, R1 = 10 kΩ 

Differential amplifier
Therefore overall gain is 
AV = Vo / (V1 − V2) = − Rf / R1 

Take A = 10 

Rf = 10 R1 
Choose R1 = 1 kΩ, Rf = 10 kΩ
# TABULATION:
![e25e398b-97b0-40bc-9063-921fcdbb1a49](https://github.com/user-attachments/assets/c4f88acf-41ed-414a-8b88-b11cf973b539)
![d69e6c45-bee7-4c12-b58f-070abf3b3bf3](https://github.com/user-attachments/assets/2999f0f3-98f5-4192-ba2c-d44749d095e0)
![8892bad0-1cd5-4974-ba31-64204f84fb14](https://github.com/user-attachments/assets/cfbf3bfb-8f29-4b23-aa7c-ee302bd88276)

# THEORETICAL CALCULATION:
![17902ad3-182a-41c7-8998-1d2113f537bc](https://github.com/user-attachments/assets/f432e87f-3767-4120-9d56-770b2401c045)
![bf03733f-983d-4fdc-9852-415400e2d1ef](https://github.com/user-attachments/assets/969966c8-7c3b-4e4f-88b3-45f9de79ea47)
![fda669df-4808-43fe-b32e-8204662d9eda](https://github.com/user-attachments/assets/923f8442-60a1-4065-8907-5f67ded3a10a)

# GRAPH:
![4b2d2eda-67e8-456b-a36a-8977c49bc3e2](https://github.com/user-attachments/assets/b92fd0af-d3ad-490b-be4e-6c2ad5bc3307)
![8ffd2e6a-9caf-4add-8601-78bd71ade3e3](https://github.com/user-attachments/assets/6e68ae7c-ce09-49d5-a979-4b853c40f8e0)

# RESULT:
