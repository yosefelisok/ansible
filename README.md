# k8s-network-policy-prj



Create a network policy to allow traffic from the Internal application only to the payroll-service and db-service

Policy Name: internal-policy
Policy Type: Egress
Egress Allow: payroll
Payroll Port: 8080
Egress Allow: mysql
MySQL Port: 3306


![image](https://user-images.githubusercontent.com/86762221/150116040-3ed10a90-5ec0-406a-8a4b-c5d90a833548.png)
