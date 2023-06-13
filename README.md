Ansible + Docker + Kotlin
=========================

This repository demonstrates how to setup a JRE 
and run a Kotlin application inside a Docker container.

1. Compile the code
   ```bash
   mvn clean package
   ``` 

2. Build and run the Docker image
   ```bash
   docker compose up -d
   ```

3. Run the Ansible Playbook
   ```bash
   ansible-playbook -vv -i inventory.cfg playbook.yml
   ```
