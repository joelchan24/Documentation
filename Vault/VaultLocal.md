# Vault in my PC

Steps of how to start my local vault instance, Validate all steps on Docker Desktop app


1. Start Vault Container
    
   Find the folder __Desktop/DevOps_SRE__ and run the Following commands
   
    ```bash
    cd Vault/Docker
    docker-compose up
    ``` 

2. Export Env variable on Powershell Terminal

    ```
    $env:VAULT_ADDR="http://localhost:8200"
    ```

3. Validate with Vault Command
   
    ```
    vault status
    ```