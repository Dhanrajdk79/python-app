python3 --version
sudo yum install python3-pip
sudo pip3 install flask
python3 -m flask --version
mkdir myflaskapp
cd myflaskapp/
python3 -m venv venv
source venv/bin/activate
sudo yum install git -y
git config --global user.name "roshanip patil”
git config --global user.email "roshani patil@hotmail.com"
git init
git pull https://github.com/ravibagale/pythonapp.git
pip install -r requirements.txt
python3 app.py

Add port no 5000 in security group .

http://ec2-public-ip:5000

---------------------------------------------------------------------
sudo su
docker build -t myimg .
docker run -d -p5000:5000 --name myflaskcontainer myimg 

