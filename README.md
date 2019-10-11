# opcpa-lps-unittests
Repository for unit tests for the OPCPA LPS 


# How to use
The OPCPA EPS unit test project imports the OPCPA EPS project as a library to run 
unit tests on the device function blocks and PLC interlocks.
1. Open the [SLAC OPCPA EPS project](https://github.com/slactjohnson/opcpa-lps).
1. In the OPCPA EPS project solution explorer right click on the 
SLAC_OPCPA_EPS->PLC->EPS->"PLC Project" icon and select "Save as library and 
install ...".
1. Save the library anywhere and let it install the library.
1. Open the SLAC OPCPA EPS Test project.
1. Configure the project to run on a 4024.0 TwinCAT installation.
1. Build the solution and confirm that it builds successfully.
1. Activate the configuration and run it.
1. The results of the unit tests will be output in the errors output.
