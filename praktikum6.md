1. ![image](https://github.com/user-attachments/assets/2ec545fc-d88d-4da0-824e-f58d8d9e401d)

2. ![image](https://github.com/user-attachments/assets/1a17c851-9307-44ed-afb6-536bdec85db0)

3. ![image](https://github.com/user-attachments/assets/faada48f-8a58-41dd-bd0c-6c07f8559412)
ps -axu | grep daemon | tr -s ' ' | awk '{print $11, $12, $13, $14, $15, $16, $17, $18}'

4. ![image](https://github.com/user-attachments/assets/665a11c0-00c0-45e6-b0d8-e811b0c0021b)
ip a | grep 'inet ' | grep -v '127.0.0.1' | awk '{print $2}' | cut -d'/' -f1 > ipaddress.txt
xargs -n1 ping -c 2 < ipaddress.txt





