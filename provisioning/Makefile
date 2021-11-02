site:
	ansible-playbook -i hosts.yml site.yml


show-initial-password:
	ansible -i hosts.yml manager -m shell -a 'cd jenkins && docker-compose exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword'