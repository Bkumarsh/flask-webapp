# Flask Web App
My first Flask project 🚀

This is a simple web application using Python Flask and MySQL database. This is used in the demonstration of the development of Ansible Playbooks.

Below are the steps required to get this working on a base linux system.

Install all required dependencies
Install and Configure Web Server
Start Web Server

# Step 1: System update
sudo apt update

# Step 2: Required packages install
Python and its dependencies
sudo apt install -y python3 python3-pip python3-dev build-essential default-libmysqlclient-dev

# Step 3: Flask + MySQL library install
pip3 install flask flask-mysql

# Step 4: Project folder create karo
mkdir webapp
cd webapp

# Step 5: app.py file banao
nano app.py

# Step 6: App run karo
python3 app.py

# Step 7: Browser me check karo
http://localhost:5000
http://<IP>:5000

# Step 8: Test URLs
http://<IP>:5000
http://<IP>:5000/how%20are%20you

# Step 9: Agar open nahi ho raha
Firewall allow karo
sudo ufw allow 5000
