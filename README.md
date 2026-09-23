# exp_4_characteristics of directional couplee


# Experiment 4 — CHARACTRISTICS OF DIRECTIONAL COUPLEE

---

## Aim

To study a microwave directional coupler and to determine its coupling factor, insertion loss, isolation and directivity.

## Apparatus Used

1 Klystron power supply. 2 Klystron tube (2K25) with mount. 3 Isolator. 4 Frequency meter. 5 Variable attenuator. 6 Directional coupler (device under test). 7 Two detector mounts. 8 Matched termination. 9 VSWR meter. 10Waveguide stands.

## Experimental Setup

<img width="940" height="312" alt="image" src="https://github.com/user-attachments/assets/674bcd16-76bf-4c4c-872a-317097a1001e" />


---

## Theory

A directional coupler is a four–port waveguide junction consisting of a primary (main) waveguide and a secondary (auxiliary) waveguide coupled to it through one or more small apertures. In a typical two–hole (Bethe–hole type) coupler, the coupling holes are spaced a quarter of a guide wavelength apart, so that the waves coupled through the two holes add constructively in the forward direction of the secondary guide and cancel in the reverse direction. This gives the device its directional property: power injected at the input port mainly couples into the secondary guide travelling toward the “coupled” port, while very little couples toward the “isolated” port. The four ports of a directional coupler are usually identified as: the input port, the transmitted (through) port on the main line, the coupled port on the secondary line (in the forward direction), and the isolated port on the secondary line (in the reverse direction, ideally carrying no power). For a two–hole coupler the holes are separated by s = λg/4, where λg is the guide wavelength at the operating frequency; this quarter–wave spacing is what makes the two coupled contributions add in the forward direction and cancel in the reverse direction. All readings in this experiment are taken directly in dB on a calibrated VSWR meter, which uses a square–law crystal detector followed by a logarithmic amplifier; hence the meter reading is already proportional to power in dB and no separate detector–law correction is required for the calculations below. The performance of a directional coupler is described by the following parameters, all expressed in decibels: the coupling factor, which is the ratio of the input power to the coupled power; the insertion loss, the ratio of input power to the power delivered at the through port; the isolation, the ratio of input power to the power leaking to the isolated port; and the directivity, the ratio of the coupled power to the power at the isolated port, which is a measure of how well the coupler distinguishes the direction of the travelling wave.

CIRCUIT / PORT DIAGRAM

<img width="686" height="306" alt="image" src="https://github.com/user-attachments/assets/34a0806b-f4f1-49c6-86ba-3aa591b607c9" />

PROCEDURE

1. The bench is set up as in Fig. 1 with the klystron tuned to give a stable output at the working frequency.
2. With the directional coupler removed, the detector is connected directly after the variable attenuator and the incident power Pi is noted on the VSWR meter.
3. Coupling factor: the coupler is inserted, the through port is terminated in a matched load, the isolated port is also terminated, and the detector is connected to the coupled port; the reading Pc is noted.
4. Insertion loss: with the coupled port terminated in a matched load, the detector is connected to the through port and the transmitted power Pt is noted.
5. Isolation / Directivity: the input and through connections are interchanged (power fed from the opposite end / through port terminated appropriately) so that power now travels toward the isolated port; the detector reading Piso at the isolated port is noted with the coupled port similarly excited for comparison. 6. All readings are recorded in dB (or converted to power) and used to compute the four parameters using the formulae below.

---

PROCEDURE FLOWCHART

<img width="1031" height="542" alt="image" src="https://github.com/user-attachments/assets/30b962f5-1bb9-4ebf-9906-b8dcaaeb9687" />

## Observation

TABULATION

<img width="1037" height="217" alt="image" src="https://github.com/user-attachments/assets/41a13bbe-4aa5-43c6-a60f-355a9385612c" />


FORMULA

1. Coupling Factor, C = Pi – Pc = 10 log10 (Pi / Pc) dB
2. Insertion Loss, IL = Pi – Pt = 10 log10 (Pi / Pt) dB
3. Isolation, I = Pi – Piso = 10 log10 (Pi / Piso) dB
4. Directivity, D = I – C dB

MODEL GRAPH AND ACTUAL GRAPH

<img width="982" height="407" alt="image" src="https://github.com/user-attachments/assets/5d5a5efc-5a0d-4f07-a35c-d66a2b3cbb5d" />


## Calculation

1. Using the average readings (Pi taken as the 0 dB reference):
2. C = 0.0 – (–19.9) = 19.9 dB
3. IL = 0.0 – (–1.05) = 1.05 dB
4. I = 0.0 – (–31.75) = 31.75 dB
5. D = I – C = 31.75 – 19.9 = 11.85 dB

## Precautions

1. All ports not being measured must be terminated in matched loads to avoid reflections that would distort the readings.
2. Connections between waveguide flanges should be tight and properly aligned.
3. The klystron output should be kept stable (constant beam and repeller voltage) throughout a set of readings.
4. The frequency meter should be de–tuned (off resonance) except when measuring frequency, to avoid an additional loss.
5. Do not look directly into the open waveguide.

result

The characteristics of the given microwave directional coupler were measured. Coupling Factor C = 19.9 dB (close to its rated 20 dB coupling), Insertion Loss IL = 1.05 dB, Isolation I = 31.75 dB, and Directivity D = 11.85 dB, values that are consistent with a typical two–hole X–band waveguide directional coupler.
