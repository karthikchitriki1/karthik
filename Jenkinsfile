node {
   stage 'Fetch code from GitHub'
   		git branch: 'main', url: 'https://github.com/helpingpeopletolearn/storyproject.git'
   stage 'Install and Start Apache'
   		sh 'sudo apt-get install apache2 -y'
		sh 'sudo service apache2 start'
   stage 'Deploy code'
   		sh 'sudo cp -R * /var/www/html/'
}