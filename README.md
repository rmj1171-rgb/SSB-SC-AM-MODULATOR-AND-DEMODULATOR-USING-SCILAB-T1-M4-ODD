# SSB-SC-AM-MODULATOR-AND-DEMODULATOR-USING-SCILAB-T1-M4-ODD
# SSB-SC-AM MODULATOR AND DEMODULATOR

## AIM

To write a program to perform SSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

> **Note:** Keep all the switch faults in off position.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the message signal.
* **Amplitude:** Maximum amplitude of the message signal.

### 2. Generate Signals:

* **Message Signal:** The baseband signal that will be modulated.
* **Carrier Signal:** A high-frequency signal used for modulation.
* **Analytic Signal:** Constructed using the Hilbert transform to get the in-phase and quadrature components.

### 3. SSBSC Modulation:

* **Modulated Signal:** Create the SSBSC signal using the in-phase and quadrature components, modulated by the carrier.

### 4. SSBSC Demodulation:

* **Mixing:** Multiply the SSBSC signal with the carrier to retrieve the message signal.
* **Low-pass Filtering:** Apply a low-pass filter to remove high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, SSBSC modulated signal, and the recovered signal after demodulation.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

---

## TABULATION

<img width="1280" height="796" alt="c1c3bc97-0d5f-431b-bf5b-0f7b46278057" src="https://github.com/user-attachments/assets/537a42dc-8f46-4f6a-b973-119babefe4a9" />


## CALCULATION
<img width="1280" height="315" alt="7b329415-df52-44ae-93c2-a0821b4a5449" src="https://github.com/user-attachments/assets/8e5ab57e-fc12-4817-babf-7c45523abbc4" />


## MODEL GRAPH
<img width="1600" height="865" alt="358b4160-25ac-42cf-82de-848133d2f150" src="https://github.com/user-attachments/assets/37490c6d-f9cf-434f-b778-1c8ca5f6b008" />

## RESULT
<img width="1156" height="867" alt="481264ae-eee7-40bc-b3b6-dfe2e49867b3" src="https://github.com/user-attachments/assets/e8999efe-c677-4f6f-bb3d-1c6915f4a5c6" />

