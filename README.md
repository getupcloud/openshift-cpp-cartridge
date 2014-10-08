# OpenShift c++ Cartridge

Uses cmake to compile your project in your OPENSHIFT_REPO_DIR with the name <app_name>_exec and runs it 
Current cmake version is cmake version 2.6-patch 4 

The example application is a simple http server, the code for which is based on the C code from http://rosettacode.org/wiki/Hello_world/Web_server#C 

To install this cartridge on OpenShift: 

	rhc app create cmake https://raw.githubusercontent.com/developercorey/openshift-cpp-cartridge/master/metadata/manifest.yml
	
This command will then clone the code to your local machine.  You can then update the code, git add, git commit, and git push.  
The code will be compiled on the server and run!

Any question, concerns, or issues? Use the issue tracker on this github repository.  
Want to add something cool to this cartridge?  Fork it and submit a Pull Request.
