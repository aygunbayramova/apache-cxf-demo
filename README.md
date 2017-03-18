# Apache CXF Contract First Service Demo

[![Build Status](https://travis-ci.org/briansjavablog/apache-cxf-demo.svg?branch=master)](https://travis-ci.org/briansjavablog/apache-cxf-demo)

Demo app uses Apache CXF to expose a simple contract first web service. Include intgeration test that deploys and test endpoint using Jetty.

Pull the source from github with git clone https://github.com/briansjavablog/apache-cxf-demo.git. To run the integration test run mvn clean install. To deploy the endpoint to Tomcat run mvn tomcat:run-war -DskipTests=true
