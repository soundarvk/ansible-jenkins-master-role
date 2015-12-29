Role Name
=========
Ansible role for installing, provisioning with all the plugins and configuring mortar Jenkins master
- Installs dependent Tomcat role
- Deploy jenkins to Tomcat
- Download plugins and provision them
- Configure jenkins based on config.yml


Requirements
------------
- ansible-cim-tomcat-role
- config.yml is encrypted with vault. Needs vault password or password file
- gradle (this role installs gradle part of it)


Role Variables
--------------
jenkins_download_url: 
tomcat_webapps_path: 
mortar_clone_url:
mortar_home_dir: 
gradle_download_url:
gradle_archive_path: 
gradle_home_dir:

Author Information
------------------
Harikrishnan Narasimhan
