# ECG-Circuit-Design 

A simple circuit which extracts an ECG signal from a patient, suppresses noise, and amplifies it. This circuit can be used for various applications- calculating heartbeat, performing further signal processing etc. 

* This circuit was simulated on LTspice XVII. Open the asc file and start simulating the design.
* Instrumentation Amplifier used is an AD8220. Click [here](https://www.analog.com/media/en/technical-documentation/data-sheets/AD8220.pdf) for the datasheet.
* In *asd-noise.ipynb*, sinusoids of particular frequencies are added to check the working of the filters. However, this is by no means a model of the real world noise.
* The red signal in *heartbeat.jpg* is an indicator of 'one heartbeat'. This is obtained by a comparator circuit. 
