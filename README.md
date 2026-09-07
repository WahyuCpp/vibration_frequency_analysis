The dataset consists of constant and variable speed data collected from 8 different D396 Marathon Electric 3-phase motors. Each motor has different types of faults artificially created by SpectraQuest. Data is collected using three accelerometers and a microphone (the first, third and fourth columns are accelerometer data, the second column is acoustic data, and the fifth column is temperature data).
The labelling of data is as follows {Letter}-{Letter}-{Number}-{Number}:

The following values represent the possibilities for the first letter:
- H indicates healthy
- R indicates rotor
- S indicates stator
- V indicates voltage
- B indicates bowed
- K indicates broken
- F indicates faulty

The second letter is represented by the following possible values:
- H indicates healthy
- U indicates unbalance
- M indicates misalignment
- W indicates winding
- R indicates rotor
- A indicates rotor bars
- B indicates bearing

The combination of both letters indicates the health state of the motor present in the data sample (e.g. H-H = a healthy motor, S-W = a stator winding fault).

The first number represents:
- 1 is for a constant speed of 15 Hz
- 2 is for a constant speed of 30 Hz
- 3 is for a constant speed of 45 Hz
- 4 is for a constant speed of 60 Hz
- 5 is for an increasing speed from 15 Hz to 45 Hz
- 6 is for an increasing speed from 30 Hz to 60 Hz
- 7 is for a decreasing speed from 45 Hz to 15 Hz
- 8 is for a decreasing speed from 60 Hz to 30 Hz

The second number represents:
- 0 for a no load condition
- 1 for a loaded condition

The duration of data collection was 10 seconds at a sampling frequency of 42 kHz. Each file contains 420,000 samples.
Raw data is provided in the folders as comma separated values files (.csv) and MATLAB files (.mat)

List of Components
#,	Component Type,	Make and Part Name,		data column #
1,	Accelerometer 1 and integrated temperature sensor, PCB 603C01, column 1 (accelerometer) and column 5 (temperature) [1]
2,	Microphone,	PCB 130F20, column 2 [2]
3,	Accelerometer 2 and 3, PCB 623C01, column 3 and 4 [3]
4,	Signal conditionner, PCB 482C 4-Channel [4]
5,	Data acquisition device, NI USB-6212 [5]
6,	Motor,	Marathon Electric D396 [6]

Selected Sensors:
Specification of each sensor that helped in setting up the data acquisition system include:
- Accelerometer 1 (model 603C01): the sensitivity rating is 100 mV/g, the frequency range is 10,000 Hz, and the measuring range is ± 490 m/s2, temperature range of +2 to +121 °C with a scale factor of +10 mV/°C [1].
- Accelerometer 2 and 3 (model 623C01): the sensitivity rating is 100 mV/g, the frequency range is 15,000 Hz, and the measuring range is ± 490 m/s2 [2].
- Microphone (model 130F20): the sensitivity is 45 mV/Pa, and the inherent noise is 29 dB [3].

References:
[1]	“PCB Piezotronics | Model 603C01.” Accessed: Oct. 26, 2023. [Online]. Available: https://www.https://www.pcb.com/products?m=603c01
[2]	“Model 130F20 | PCB Piezotronics.” Accessed: September. 18, 2023. [Online]. Available: https://www.pcb.com/products?m=130F20
[3]	“PCB Piezotronics | Model 623C01.” Accessed: Oct. 26, 2023. [Online]. Available: https://www.pcb.com/products?model=623c01
[4]	“Series 482.” Accessed: September. 20, 2023. [Online]. Available: https://www.pcb.com/sensors-for-test-measurement/electronics/line-powered-multi-channel-signal-conditioners/series-482-4-channel
[5]	“USB-6212.” Accessed: Nov. 02, 2023. [Online]. Available: https://www.cnrood.com/en/781003-01
[6]	“Marathon Electric D396, 3 Hp, 3600 Rpm, 56HC FR, 230/460 Vac, 3 PH, TEFC, C-Face Footed, General Purpose, Standard Efficiency, 56T34F5306.” Accessed: Nov. 10, 2023. [Online]. Available: https://www.industrialmotors.com/marathon-electric-d396-3-hp-3600-rpm-56hc-fr-230-460-vac-3-ph-tefc-c-face-footed-general-purpose-standard-efficiency-56t34f5306.html