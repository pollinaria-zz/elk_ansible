# elk_ansible
project from logz.io with some changes

in file /roles/filebeat/defaults/mail.yml need to change line 

`filebeat_output_logstash_hosts:`

`  - "0.0.0.0:5044"`
 
 to your actual elk-server address.
