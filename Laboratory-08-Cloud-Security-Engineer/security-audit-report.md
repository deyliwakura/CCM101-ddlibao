# Security Audit Report

## 1. Principle of Least Privilege

The Principle of Least Privilege means giving users, applications, and services only the permissions they need to perform their tasks. This reduces the risk of unauthorized access and limits the damage if an account or application is compromised. In this mission, allowing only the necessary network ports follows this principle.

## 2. Attack Surface

The attack surface refers to all the possible points where an attacker could attempt to access or compromise a system. Open network ports, running services, and unnecessary applications can increase the attack surface. Deploying only necessary services and restricting access to required ports can help reduce security risks.

## 3. Default Deny Policy

A Default Deny Policy blocks incoming network connections unless a specific firewall rule allows them. This approach helps prevent unauthorized access to services that do not need to be publicly accessible. In this mission, UFW was configured to deny incoming traffic by default while allowing SSH and the web server's TCP port 8080.

