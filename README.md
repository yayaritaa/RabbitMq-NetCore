# RabbitMq-NetCore
Net Core 2.1 and RabbitMq simple producer and consumer 



Install Erlang => http://www.erlang.org/downloads
Install RabbitMQ => http://www.rabbitmq.com/install-windows.html

cmd.
C:\Program Files\RabbitMQ Server\rabbitmq_server-3.7.9\sbin\rabbitmq-plugins.bat enable rabbitmq_management

restart RabbitMq Service and check http://localhost:15672/ 
default port 15672 deafult username and password for rabbitMQ dashboard is "guest"
https://github.com/EnesAys/RabbitMq-NetCore/blob/master/rabbitMQ-Dashboard.JPG

For .Net Core producer and consumer add packages via Nuget or package manager console

Install-package Newtonsoft.Json
Install-package RabbitMQ.Client

https://github.com/EnesAys/RabbitMq-NetCore/blob/master/rabbitMQ.gif

