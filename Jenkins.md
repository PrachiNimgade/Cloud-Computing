# Steps to install Jenkins

* sudo apt update -y
  
 ![1](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/a2c7922d-7730-49d7-8222-da01b452f98f)

* sudo apt upgrade -y

  ![2](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/2e18d993-e341-4857-9bf2-1d0acd4e2648)

* sudo apt install openjdk-11-jre

  ![3](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/74d10a64-1720-4ef5-a00a-d9d425305595)

![4](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/a488acc0-d07b-476f-a2d3-bd24d5dc6bd3)

* sudo curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo tee   /usr/share/keyrings/jenkins-keyring.asc > /dev/null

  ![5](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/041e2331-3669-440b-84b6-427c3413020f)

* sudo echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]   https://pkg.jenkins.io/debian-stable binary/ | sudo tee   /etc/apt/sources.list.d/jenkins.list > /dev/null

  ![5](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/7126ee7c-e424-404f-9c5c-c7622db79ef4)

* sudo apt-get update

  ![6](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/1ac3eea0-9a6e-4153-adcf-50a037ddf25b)

* sudo apt-get install jenkins -y

  ![7](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/3c59fdaa-bfb5-4adc-ae25-6b9e6b1767ec)

* sudo systemctl status jenkins
  
![15](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/9e0364a7-c0db-42e3-9e81-9009f1e5c9b5)

* sudo systemctl start jenkins
* sudo systemctl enable jenkins
  
* cat /var/lib/jenkins/secrets/initialAdminPassword
  
                6acd7106d6a64918936c5f93a910f232

  ![8](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/66634f79-d22e-4e1b-938f-626c2c993da6)

  
  ![9](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/23dcc71f-b5bf-486e-8ad1-382d85fb04ce)

![10](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/a5bd95cf-8a57-441e-bded-e7044b515aa4)


![11](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/33b4fe2d-76a4-4f22-a17f-22bab34bf952)


![12](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/04df3d30-850c-439a-be8b-ca496dc20732)


![13](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/4825fca2-747d-451a-b248-2169e7d94bc7)


![14](https://github.com/PrachiNimgade/Cloud-Computing/assets/113961419/e47b61d1-0ae3-4d1a-b1d2-c00880a70fa4)
