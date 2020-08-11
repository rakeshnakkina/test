# test

Step 1:
i run maven install from my end and attached war file
RakeshTechTest.war

Step 2:
Git clone & Please run Docker file (attached )
Run below commands
    docker build -t test .
    check docker images
    docker run -d -p 8080:8080 test

Step 3:
 verify URL below
 http://localhost:8080/ping  -- output should be OK
 http://localhost:8080/      -- -- output should be Success
    
