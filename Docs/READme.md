AWS cluster for Deploy Django-WebApp application

 step 1- Create a AWS EC2 machine

 step 2- Install Git packages on a AWS ec2 machine

 ```sh
 # Update the package list
sudo yum update -y

# Install Git
sudo yum install git -y

# Verify the installation
git --version   sh```

step 3- Install Docker packages on AWS ec2 machine

  ```sh
# Update the package list
sudo yum update -y

# Install Docker
sudo yum install docker -y

# Start the Docker service
sudo service docker start
sudo systemctl enable docker

# Add your user to the Docker group
sudo usermod -aG docker ec2-user


 step 4- Install and configure a Jenkins on aws ec2 machine.

 step 5- install kubectl and configure it with EKS.
