# Internship-Project

EC2 machine
sudo apt install
sudo apt install openjdk-11-jre
curl -fsSL https://pkg.jenkins.io/debian/jenkins.io.key | sudo tee /usr/share/keyrings/jenkins-keyring.asc > /dev/null
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] https://pkg.jenkins.io/debian binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins
Now, add a rule and add a port of 8080 and set info as [0,0.00/0]
systemctl status jenkins
systemctl start jenkins
systemctl enable jenkins
Now enter <public IP add of EC2 machine:8080> in browser
