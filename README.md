# k8s-network-policy-prj



Create a network policy to allow traffic from the Internal application only to the payroll-service and db-service

Policy Name: internal-policy
Policy Type: Egress
Egress Allow: payroll
Payroll Port: 8080
Egress Allow: mysql
MySQL Port: 3306
