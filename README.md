step1: installation of apache web server in two different server from ansible controller machine.
step2: creating a hostfile with target ip adddress, username and password.
step3: creating one more variable in hostfile (apache_port).
step4. creating a apache.j2 file in local server.
step5. using template, changing the configuration file of two target server using apache.j2 file.
step6. restarting the service using handlers.
