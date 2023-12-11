Vagrant Multi-Tier Web App Deployment

Overview

This project demonstrates the deployment of a Multi-Tier Web Application locally using Vagrant. It utilizes various technologies to set up different services, including Nginx (Web Service), Tomcat (Application Server), RabbitMQ (Broker/Queuing Agent), Memcache (DB Caching), ElasticSearch (Indexing/Search service), and MySQL (SQL Database).

Prerequisites
Before getting started, make sure you have the following prerequisites installed:
1. Oracle VM Virtualbox
2. Vagrant

Getting Started
1. Clone the Repository:

     git clone https://github.com/Abhangiri/VagrantMultiTierWebApp.git


2. Install VirtualBox and Vagrant:

   Make sure you have VirtualBox and Vagrant installed on your machine.

3. Run Vagrant:
       vagrant up


Project Structure

Vagrantfile: Contains the configuration for your Vagrant environment.
provision.sh: Bash script for provisioning the different services

Services

Nginx (Web Service):
  Nginx is configured to serve as the web service.

Tomcat (Application Server):
  Tomcat serves as the application server.

RabbitMQ (Broker/Queuing Agent):
  RabbitMQ is used as the message broker.

Memcache (DB Caching):
  Memcache is employed for database caching.

ElasticSearch (Indexing/Search service):
  ElasticSearch handles indexing and search functionality.

MySQL (SQL Database):
  MySQL serves as the SQL database.


Vagrant Commands 

Here are some useful Vagrant commands to manage the virtual machines:

vagrant up: Create and provision the virtual machines.
vagrant halt: Gracefully shut down the virtual machines.
vagrant destroy: Remove the virtual machines. This will delete all data inside the virtual machines, so use with caution.
vagrant ssh [machine-name]: SSH into a specific virtual machine.


