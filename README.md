# adding-ssh-key
1. `ssh-keygen -t rsa -b 4096 -C "samantha.owusuantwi@duke.edu"`  
2. press enter to accept defailt file location for key  
3. press enter to leave passphrase blank  
4. `cat ~/.ssh/id_rsa.pub`  
5. copy and paste key into SSH section of settings in github  
6. THEN clone the repository and identify yourself before makign commits/pushing:  
`global user.email "samantha.owusuantwi@duke.edu"`  
`git config --global user.name "Samantha Owusu"`
