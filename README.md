# cloud_vm_networking_flask
### Rozelle Barao Thompson
### Cloud provider: GCP

### Video Recording 
https://www.loom.com/share/e674dfec47104f7a9e942c5ffc007204?sid=4ae9c770-6935-423b-b26f-56360d4291ec

## Steps

### 1. VM Creation
![VM_created](images/vm_creation.png)

### 2. Networking (Port 5003 Open) 
![Port_5003](images/firewall.png)

### 3. OS Update + Python Install 
- #### Commands
  - **Update OS:**  sudo apt update && sudo apt upgrade -y
  - **Insall Git, Python3 + pip:** sudo apt install git python3 python3-pip python3.13-venv -y
![Python_install](images/python_install.png)

### 4. Flask App Running 
![Flask_run](images/flask.png)

### 5. Public IP Access
- URL: https://34.132.123.240:5003
![Public_URL](images/public.png)



