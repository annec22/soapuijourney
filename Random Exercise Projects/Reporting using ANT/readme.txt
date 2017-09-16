Reporting using ANT.

Use ANT and JUNIT

	1. First PATH and ANT_HOME must be set to in Environment Variables..
		a. ANT /bin in eclipse installation path can be used
	2. check if correctly installed:
		ant -version
	3. Create SoapUI Project and save it to any location. The ".xml" project file saved will be used.
	4. execute ant


When executing ant, it will automatically search for build.xml.

To execute test suite from the command prompt, use:

testrunner.bat -r -j -f 'C:\Path\to\place\report' -s'Smoke Test Suite' 'C:\Path\to\TestSuite.xml'