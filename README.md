# raptor_soc_template
Raptor is an SoC Design Template based on Arm Cortex M0 or M3 core.

**Efabless**, San Jose CA

## Project Structure
The SoC template example is composed of two sets of files:

###soc files
'**soc**' files decribe the overall architecture as well as 
fixed design elements

###ip files
'**ip**' files describe each of the IP blocks and peripherals referenced by the SoC.  Within each category, there are 'definition' and 'design_files'.  

##Definition files
'**definition**' files provide attrbutes in the form of a structure set of key-value pairs.  They provide attributes of the design element within the system.

##Design files
'**design files**' are parameterized templates for verilog, firmware, testbenches, etc.  Final versions of these files are generated by a compiler based on the configuration of the SoC.

Examples for this SoC use embedded java script supporting automated compilation of the design files.  

NOTE:  Current design file examples are provided for initial reference.  These files are currently being updated and will be reposted once complete.

##SoC Instance Example

An example of an SoC configuration is provided.  This example represents the demo chip taped-out by Efabless on X-FAB 180nm process (XH018).  The demo chip provides a working implementation of the SoC that can be used to evaluate functionality or build proof-of-concepts.