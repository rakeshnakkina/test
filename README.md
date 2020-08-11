# test

Step 1:
I have run maven commands from my end to create war file & attached war file
WAR file name : RakeshTechTest.war

Step 2:
Git clone & Please run Docker file (attached )
Run below commands
    docker build -t test .
    check docker images
    docker run -d -p 8080:8080 test

Step 3:
 verify URL below
 hhttp://localhost:8080/RakeshTechTest/ping  -- output should be OK
 http://localhost:8080/RakeshTechTest/      -- -- output should be Success
    
