# 📘  Vault In Local Machine

**Date:** 18/01/2025  
**Level:** 🚀 Básico  
**Estimated duration:** ⏱️ 5 minutes  
   
---

## 🎯 **Post Objective**

Steps of how to start my local vault instance, Validate all steps on Docker Desktop app

---

## 🔧 **Prerequisites**

Before getting started, make sure you have the following:

1. [Docker](https://docs.docker.com/engine/install/) Installed on machine 
2. Docker Compose 
3. Vault Installed on machine

---

## 🚀 **Step-by-Step Instructions**

###  **Step 1: Start Vault Container**

   Find the folder __Desktop/DevOps_SRE__ and run the Following commands
   
```bash
cd Vault/Docker
docker-compose up
``` 

###  **Step 2: Export Env variable on Powershell Terminal**

   Export the variable using powershell sintax
   
```
$env:VAULT_ADDR="http://localhost:8200"
```

###  **Step 3:  Validate with Vault Command**
   
```
 vault status
```