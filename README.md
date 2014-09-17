Pre-Requisites 
•          Ant installed: http://ant.apache.org/
•          Emma installed: http://emma.sourceforge.net/
Installation:
•          Create Emma directory and copy the contents (lib, build.xml). 
           Ex:  Emma/build.xml
•          Under Emma/ dir, execute “ant -f build.xml”
•          Restart Jboss
•          Run Tests
•          Under Emma/ directory, execute “ant –f build.xml report”
•          Copy coverage.html and _files to view the report. 

Explanation of Script:
Step 1: Set class path to include Emma and ANT binaries
Step 2: Settings to use ANT tasks
Step 3: Initialize directories
Step 4: Instrument the .jar's/.classes/.war's/.ear's
Step 5: Collect the data from JVM Port runtime
Step 6: Generate Coverage Report
