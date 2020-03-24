# playbooks
Collection of miscellaneous ansible playbooks

os_to_csv.yml :
  
    grabs os version of all online nodes and outputs to csv file

update_user.yml :
     
    create user/update user password and group

uptime_output.yml :

    grab uptime from all hosts and output to file
    
hdd_space.yml :

    display "df -h" command stdout to terminal during runtime

remove_user_list.yml :
  
    remove list of users from nodes
    
remove_user.yml :

    remove single user from nodes

raw_command.yml :

    run raw command 
    
simple-file-stage.yml :

    copy 2 local files to remote servers
    
grab_file.yml :

    grab report files from remote servers (following $IP.report naming convention)
    
mass-cve-check.yml :

    after creating a local list of cves, this playbook will copy the cvelist to all remote servers and check to see which ones were patched
