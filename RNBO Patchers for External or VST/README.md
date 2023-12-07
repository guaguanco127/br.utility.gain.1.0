# Max/MSP RNBO PAtches for External of VST Creation: br.utility.gain-1.0  
   
By Brian Riordan  
[guaguanco127@gmail.com](mailto:guaguanco127@gmail.com)  
[brianriordanmusic@gmail.com](mailto:brianriordanmusic@gmail.com)  
Repository for br.utility.gain-1.0, with all related filtes, can be found here: [https://github.com/guaguanco127/br.utility.gain-1.0](https://github.com/guaguanco127/br.utility.gain-1.0)  
Additional programs can be found here: [https://github.com/guaguanco127](https://github.com/guaguanco127)

These files were created with Max/MSP version 8.5.6. and RNBO 1.2.3

## Table of Contents 

[About](#About)   
[What is an External for Max/MSP?](#External)  
[What is a VST or AU Audio Plugin?](#VST)  
[How To Export as a Max/MSP External](#Export)  
[How To Export as a VST or AU Audio Plugin](#ExportVST)  

 
 

## <a name="About"></a>About

There are two Max/MSP patches in this folder.  

br.utility.gain.rnbo.ext_1.0 is a patch set up to export as a Max/MSP external.  

br.utility.gain.rnbo.vst_1.0.maxpat is a patch set up to export as a VST or AU audio plugin.  

Either program allows the user to adjust a the volume of a stereo signal. The decibel range is from -72 dB to +35 dB.
-72 dB is converted to negative infinity dB.
Currently works in any sample rate or bit depth.  

## <a name="External"></a>What is an External for Max/MSP?

An external is a type of object that does not come with your Max/MSP library. Unlike the typical objects that you can call on all versions of Max/MSP, an external must be installed on the users computer a specific way. 

## <a name="VST"></a>What is a VST or AU Audio Plugin? 

A VST is a third party audio plugin generally run within a digital audio workstation (DAW). A VST is cross platform for both Windows and Macintosh. An AU works the same way but is exclusively for Macintosh. 


## <a name="Export"></a>How To Export as a Max/MSP External

1. Make Sure Max/MSP 8 is installed in your computer, and make sure you have a license for RNBO as well.

2. Open up br.utility.gain.rnbo.ext_1.0.maxpat using Max/MSP 

3. Double-click on the [rnbo~] object while the patch is locked.

4. Click on "Show Export Sidebar" on the right hand side 

5. Select "Max External Export"

6. Select settings needed to create a Max External. Make sure you name the object. 

## <a name="ExportVST"></a>How To Export as a VST or AU Audio Plugin

1. Make Sure Max/MSP 8 is installed in your computer, and make sure you have a license for RNBO as well.

2. Open up br.utility.gain.rnbo.vst_1.0.maxpat using Max/MSP 

3. Double-click on the [rnbo~] object while the patch is locked.

4. Select "Audio Plugin Export"

5. Select settings needed to create a VST (or AU), and select the platform. Make sure you name your plugin. 



    



 




