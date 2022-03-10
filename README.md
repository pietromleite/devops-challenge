# Acesso
Acesso SSH
- Host: ec2-3-88-190-84.compute-1.amazonaws.com
- User: ec2-user
- Private Key: aws-pietro.pem (enviado por e-mail)

RDS
- DB_HOST: wordpress-pietro.ccjvfewblenh.us-east-1.rds.amazonaws.com
- DB_NAME: wordpress-pietro
- DB_USER: wordpress_pietro
- DB_PASSWORD: wordpress123

# Comandos de instalação
curl -sSL  https://raw.githubusercontent.com/pietromleite/docker-compose/main/wp.sh > wp.sh
sh wp.sh

# Detalhamento do processo
Arquivos:
- wp.sh: Instalação 
- docker-compose-yml: configuração


