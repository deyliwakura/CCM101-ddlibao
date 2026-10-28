# Multi-Tier Architecture

## Two-Tier Architecture

A two-tier architecture separates an application into two main parts: the Web/Application Tier and the Database Tier.

## Web/Application Tier

The Web/Application Tier handles user requests and provides the application's web interface. In this activity, Nextcloud is the application tier.

## Database Tier

The Database Tier stores persistent data such as user accounts and application information. In this activity, MariaDB is the database tier.

## Why Separate Them?

Separating the web server and database into different containers makes the system easier to manage and maintain. Each container can be updated or restarted independently, and the separation improves organization and scalability.
