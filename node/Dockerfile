FROM centos

# Update ec2 instance
RUN yum update -y

# Enable Extra Packages for Enterprise Linux (EPEL) for CentOS
RUN     yum install -y epel-release
# Install Node.js and npm
RUN     yum install -y nodejs npm
# Install git
RUN     yum install -y git 

EXPOSE  8080
