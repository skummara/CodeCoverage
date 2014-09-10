CodeCoverage
============

Analysis of Functional Code Coverage


Emma Code Coverage :

Pre-Request
•	Ant installed: http://ant.apache.org/
•	Emma installed: http://emma.sourceforge.net/ 

Usage :

 ant -f build.xml -Demma.dir=. -Ddeploy.dir=/usr/local/jboss/server/default/deploy -Ddeploy.lib=/usr/local/jboss/server/default/lib/
 ant -f build.xml -Demma.dir=.  report

Emma Code coverage :
•	Create Ant Build File. Eg emma/build.xml
•	Stop Jboss
•	Under emma/ dir, execute “ant -f build.xml”
•	Start Jboss
•	Run Tests
•	Under emma/ dir, execute “ant report”
Emma code coverage collect to emma/coverage.ec and generates coverage report file coverage.html and _files
•	Copy coverage.html and _files to view the result.
