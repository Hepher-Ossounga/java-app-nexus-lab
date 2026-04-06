# Java Web App

A simple Java Maven application for practicing Nexus Repository Manager deployment.

## Setup

1. Replace `NEXUS_EC2_PUBLIC_IP` in `pom.xml` with your actual Nexus server public IP.
2. Configure `~/.m2/settings.xml` with your Nexus credentials.
3. Run `mvn deploy` to build and deploy to Nexus.

## Requirements

- Java 8
- Maven
- Nexus Repository Manager running on port 8081
