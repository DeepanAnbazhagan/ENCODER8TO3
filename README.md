# ENCODER8TO3
# AIM:
To simulate and synthesis of Encoder using Vivado software.
# APPARATUS REQUIRED:
Vivado 2023.1 software.
# Pin Diagram:
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/824226c8-c767-44b5-ab35-26fed65b195e)
# Truth Table:
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/e228c14b-b814-40c8-92eb-748d48570c04)
# Circuit Diagram:
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/6fa5fe84-fe6f-472d-b9c0-e6dfa17413d3)
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/7d147e2a-ba03-4714-baee-17615c9c50c1)
# Program:
     module encoder8to3(a0,a1,a2,d0,d1,d2,d3,d4,d5,d6,d7);
     input d0,d1,d2,d3,d4,d5,d6,d7;
     output a0,a1,a2;
     assign a0 = d1 | d3 | d5 | d7 ;
     assign a1 = d2 | d3 | d6 | d7 ;
     assign a2 = d4 | d5 | d6 | d7 ;
     endmodule
# Elaborated Design:
<img width="960" alt="Screenshot 2024-03-25 234343" src="https://github.com/DeepanAnbazhagan/ENCODER8TO3/assets/164902865/483a5c6a-d163-4473-b162-8bfb91328c98">

# Output: 
<img width="960" alt="Screenshot 2024-03-25 234302" src="https://github.com/DeepanAnbazhagan/ENCODER8TO3/assets/164902865/c056bbad-c8cc-47d2-bfa0-366fbcd34947">

# RESULT:
Thus the simulate and synthesis of Encoder is verified successfully by using Vivado software.
  

