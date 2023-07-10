# Development of a method that leverages X-ray attenuation to detect thin film thickness with a 
resolution of +-5nm in the range of 50nm to 1 um
-
\ The goal of the project is to construct a setup that can measure sample thickness (using Beer Lambert's Law) to maintain uniformity of the sample.         
\To count the photons that pass through the sample, an X-Ray gun is positioned in front of it, and the detector is positioned behind it. Two detectors, a Minipix and a Silicon pin detector (which are connected to an amplifier and the amplifier is connected to a Multi-channel Analyzer, which is used to digitalize the signal and acquire the spectrum), have been used to evaluate the spectrum and the number of counts collected. Roentgen (a Python module) has been used to validate the results.  	
\ Although the setup producesprecise findings at the micron level, there are significant variations in the number of counts when using copper sheets that are around 100 nanometers thick.   	My current work entails probing and identifying strategies to lessen variances at the nanoscale level.
