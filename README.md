# Deploying a Flask API and MySQL server on Kubernetes

This repo contains code that 
1) Deploys a MySQL server on a Kubernetes cluster
2) Attaches a persistent volume to it, so the data remains contained if pods are restarting
3) Deploys a Flask API to add, delete and modify users in the MySQL database
