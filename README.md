# ansible-task
Steps:
1. Change the Super user with your super use in .YML file<br />
2. Update the inventory file with your cluster of hosts<br />
3. Run the Ansible Playbook with the below command<br />

ansible-playbook -i inventory_file --ask-sudo-pass deploy_authorized_keys.yml


# Kubernetes-task
Steps to follow for running this scripts in a K8s environment.<br />
1- Extract this zip and place it in a directory.<br />
2-go inside the directory where weatherapp.json is located.<br />
3-Jusr run simple kubectl create -f weatherapp.json.<br />
this will fetch the latest weather file and deploy this pod to the K8s environment<br />

just simple run on the browser. 
http://localhost:8080/weather/gettemperature/{city or zip code}

Test cases:<br />
http://localhost:8080/weather/gettemperature/201305<br />
http://localhost:8080/weather/gettemperature/Noida<br />
http://localhost:8080/weather/gettemperature/Delhi<br />
http://localhost:8080/weather/gettemperature/202138
