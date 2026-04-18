<img width="1919" height="1079" alt="Screenshot 2026-04-18 133517" src="https://github.com/user-attachments/assets/b3cd7696-88ed-42b7-9831-ae70be4ae071" />
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**

<img width="1600" height="1144" alt="image" src="https://github.com/user-attachments/assets/87500277-340f-44d1-8009-55875013946c" />



---

## Graphs

*(Insert plots of Optical Power, Q Factor, and BER vs. Fiber Length here)*

<img width="1919" height="1079" alt="Screenshot 2026-04-18 133517" src="https://github.com/user-attachments/assets/d8014a8f-1959-476f-b30c-7fe123691ba5" />
<img width="1919" height="1079" alt="Screenshot 2026-04-18 133547" src="https://github.com/user-attachments/assets/a4a71615-9acc-41f6-b5ab-f5708b9531d2" />
<img width="1919" height="1079" alt="Screenshot 2026-04-18 133614" src="https://github.com/user-attachments/assets/b77a1aaf-a397-4693-8db8-6965ad10540b" />
<img width="1919" height="1079" alt="Screenshot 2026-04-18 133635" src="https://github.com/user-attachments/assets/66d02d5f-565d-419f-99bd-66e92c5ac107" />
<img width="1919" height="1079" alt="Screenshot 2026-04-18 133654" src="https://github.com/user-attachments/assets/1ba86400-48b1-4afe-8aad-d985bb3edf19" />





## RESULT

*(Summarize key findings from simulation and analysis)*

