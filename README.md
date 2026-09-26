# Generation-and-detection-of-AM-using-SCILAB---T1---M4---ODD
# AIM

To generate and detect the amplitude modulation and demodulation using SCILAB and to calculate modulation index of AM.

# EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

# THEORY

Modulation can be defined as the process by which the characteristics of carrier wave are varied in accordance with the modulating wave (signal). Modulation is performed in a transmitter by a circuit called a modulator.

Need for modulation is as follows:

* Avoid mixing of signals
* Reduction in antenna height
* Long distance communication
* Multiplexing
* Improve the quality of reception
* Ease of radiation

Amplitude Modulation is the process of changing the amplitude of a relatively high frequency carrier signal in proportion with the instantaneous value of the modulating signal. The output waveform contains all the frequencies that make up the AM signal and is used to transport the information through the system. Therefore the shape of the modulated wave is called the AM envelope. With no modulating signal the output waveform is simply the carrier signal. Coefficient of modulation is a term used to describe the amount of amplitude change present in an AM waveform. There are three degrees of modulation available based on value of modulation index.

1. **Under modulation:** `m < 1`, `Em < Ec`
2. **Critical modulation:** `m = 1`, `Em = Ec`
3. **Over modulation:** `m > 1`, `Em > Ec`

**Note:** Keep all the switch faults in off position.

# ALGORITHM

### 1. Define Parameters

First, define the parameters for your signals:

* Carrier frequency (fc)
* Modulating signal frequency (fm)
* Sampling frequency (Fs)
* Duration of the signal (T)

### 2. Create Time Vector

Create a time vector based on the sampling frequency and duration.

### 3. Create Modulating Signal

Define the modulating signal (message signal).

### 4. Create Carrier Signal

Define the carrier signal.

### 5. Perform Amplitude Modulation

Multiply the carrier signal by the modulating signal plus 1 (to ensure the modulation depth).

### 6. Plot the Signals

Visualize the modulating, carrier, and modulated signals.

### 7. Demodulate the AM Signal

To demodulate, you can use envelope detection. One way is to rectify the signal and then apply a low-pass filter.

### 8. Plot the Demodulated Signal

Visualize the demodulated signal.

### 9. Compare Signals

Compare the original modulating signal with the demodulated signal.

# PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.
## Model graph
<img width="503" height="350" alt="image" src="https://github.com/user-attachments/assets/2e10c9cc-39fa-40d2-8246-d1cf6e26e122" />


# TABULATION
<img width="720" height="1280" alt="WhatsApp Image 2026-09-18 at 11 12 07 PM" src="https://github.com/user-attachments/assets/546b2628-df1f-4d52-9777-52fe14660975" />



# CALCULATION

<img width="720" height="1280" alt="WhatsApp Image 2026-09-18 at 11 12 50 PM" src="https://github.com/user-attachments/assets/2ab8ab45-24fe-4aa3-a1e5-b1ab0944c12d" />
<img width="848" height="1280" alt="WhatsApp Image 2026-09-18 at 11 13 11 PM" src="https://github.com/user-attachments/assets/c1e08f41-e0b9-48c6-b27b-64594c4801fb" />


## Output
<img width="1917" height="1021" alt="Screenshot 2026-09-18 232107" src="https://github.com/user-attachments/assets/3820d5d8-3625-4a19-bc82-73532e7ea544" />

## MARK SPLIT UP
<img width="1280" height="915" alt="image" src="https://github.com/user-attachments/assets/2208c28b-193e-4405-a439-bebc3e6b827f" />



## Result

Successfully generated and detected the amplitude modulation and demodulation using SCILAB and to calculate modulation index of AM.




