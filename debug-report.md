
1. Problem - Port 80 not allowing ngnix
2. Root Cause - nginx installed locally 
3. How found - using the ss -tunlp | grep :80 command
4. Fix apply - uninstall the local nginx
5. Result - Allocated the port 80 for nginx container


1. Problem - The ngnix container getting restart continously 
2. Root Cause - docker-copmpose.yaml file crashed
3. How found - Using internet
4. Fix apply - recreate the container using "docker compose up -d --force-recreate nginx" command 
5. Result - container up and run


1. Problem - git commit not working
2. Root Cause - after adding the key not run the neccesary command on the server
3. How found - from the error massage
4. Fix apply - run the "git remote set-url origin <ssh url>"
5. Result - Commit work and workfloor got triggered
