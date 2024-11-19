# FinalMiniNet

Configurando uma topologia linear com 8 hosts com mac padronizados, com controle de trafego e largura de 30mbps

![WhatsApp Image 2024-11-18 at 09 38 57](https://github.com/user-attachments/assets/17acbfb4-0728-4dc6-ab70-9d8a423741ec)


Pings entre todos os pares de hosts e exibe uma matriz de conectividade com possíveis perdas de pacotes.

![image](https://github.com/user-attachments/assets/0c015497-6293-4f8b-afc3-9603ce0ad6d9)

![image](https://github.com/user-attachments/assets/e2988312-5bf6-48f8-8685-2f9e6344c148)

iniciando o iperf no modo servidor na porta 5555, na segunda imagem, especifica a porta, define a largura para 30, o tempo de teste para 15 e gera um relatorio por segundo

![image](https://github.com/user-attachments/assets/d88db6c6-4779-44e9-a8a5-d77624408b48)

Tamanho 1.5 mb


![image](https://github.com/user-attachments/assets/dea495d4-2e48-46cf-a302-28f872b81fe3)

Tamanho 10 mb


![image](https://github.com/user-attachments/assets/6449befb-22e8-4c9d-ad81-c5f0e6c55c9d)

Tamanho 15 mb


![image](https://github.com/user-attachments/assets/e2bbd398-4750-4359-b13a-61f5993fc65d)

Tamanho 20 mb 

![image](https://github.com/user-attachments/assets/b3eb049d-2ce9-4f35-94a7-08ac4f3a1bf6)


Tamanho 25 mb


![image](https://github.com/user-attachments/assets/791329ca-4843-4b23-8848-f5d496cbd2a8)

Lista as interfaces, os endereços mac, ip e portas, e também testa a conectividade entre os hosts na rede


![image](https://github.com/user-attachments/assets/34570f93-f9e8-4a6c-a6ad-aeda4a0b82f1)

Topologia com as informações do item anterior


![image](https://github.com/user-attachments/assets/8227ca78-5d2a-4e44-bfa9-0e3356b10196)


Apagar as regras existentes e adicionar novas regras baseadas em mac (permite comunicação entre h1 e h2, e de h1 e h3, enquanto bloqueia a comunicação entre outros hosts


![image](https://github.com/user-attachments/assets/178bac1e-3939-4326-8f53-fce5e3b22a4b)

