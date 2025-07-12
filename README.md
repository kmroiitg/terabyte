The program is suitable with the following setup - (I) THOR LABS LTS-300 travel stage (II) Stanford research systems SR380 Lock-in amplifier. 
The program uses library files obtained from the website for the instruments - THOR (https://github.com/Thorlabs/Motion_Control_Examples/tree/main) and SR380 (https://pymeasure.readthedocs.io/en/latest/api/instruments/srs/sr830.html)
Run the notebook to start the program. Make sure the instruments are powered on. 
Replace the serial number in the program with the actual serial number of your LTS, and also verify the VISA number for lock-in.

For different models, script can be modified accordingly, by importing their python drivers. The aim of this project is to help understand the "flow" of data collection process in a THz-TDS setup. 
