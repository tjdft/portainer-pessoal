## Portainer gerenciador de Conteiners CE
![image](https://user-images.githubusercontent.com/1260578/129073002-bfd18698-3439-4704-9ee1-7af4b2bf33c7.png)


Aplicação para gerenciamento e monitoramento de containers local (Docker)
Configurado para ambiente local de Desenvolvimento

# Na criação do pod é necessário estar fora da VPN

### Basta executar esse comando depois do clone
```console
docker-compose up -d

# Para inicializar o portainer na sua maquina digite:
./start
```

### Acessar via URL do Browser

http://localhost:9990

Ao acessar configurar o password e selecione o docker localmente

## Push an existing folder
```console
cd existing_folder
git init
git remote add origin https://github.com/tjdft/portainer-pessoal.git
git add .
git commit -m "Initial commit"
git push -u origin master
```
