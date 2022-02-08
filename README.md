## Title

![image](https://user-images.githubusercontent.com/79367834/152848457-55e7f2e6-e2ea-4145-9c2a-bc70e94dbdd7.png)




##
Installation

pip install django

npm install chart.js

pip install mysql

##
Usage

Import django.urls

import Views

import models

import requests

import Blockchain

import BeautifulSoup




##
Example

admin.site.register(Blockchain)

class Blockchain(models.Model):
    address = models.CharField(max_length=100, null=False, blank=False)
    balance = models.IntegerField()

    def __str__(self):
        return f'{self.address} - {self.balance}'
    
    
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'djangoecom',
        'HOST': 'localhost',
        'USER': 'root',
        'PASSWORD': '',
        'PORT':'3306',
    }
}



![image](https://user-images.githubusercontent.com/79367834/152848911-3564d06d-0cec-47b3-a6c3-4aed8835b91b.png)
![image](https://user-images.githubusercontent.com/79367834/152848976-a5e7d813-82f3-4889-b838-7b858689685a.png)
![image](https://user-images.githubusercontent.com/79367834/152849036-e691f47a-2cc7-44d4-a9f4-1dc465e1a3fe.png)
![image](https://user-images.githubusercontent.com/79367834/152943040-8b154032-5355-46b7-9d01-ebf9527058f0.png)
![image](https://user-images.githubusercontent.com/79367834/152943076-67247b94-efa9-4e1a-a2bb-5092c03b8d8a.png)


