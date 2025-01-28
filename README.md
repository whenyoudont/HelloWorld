# HelloWorld

```
sudo wget -O /usr/share/keyrings/jenkins-keyring.asc https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key

echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list > /dev/null

sudo apt update

sudo apt install jenkins -y

sudo apt install -y openjdk-17-jre

sudo systemctl start jenkins

sudo systemctl status jenkins
```

## 
Pipelines

* https://github.com/TheEarlOfGray/simpleflaskapp
```
sudo apt install python3-pip
```
```
pip install -r requirements.txt
python3 app.py
```

* https://github.com/QA-Instructor/lbg-vat-calculator
```
sudo apt install -y npm nodejs
```
```
npm install
npm start
```
