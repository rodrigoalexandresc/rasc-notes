Passo para execução do postgres
- Instalar distro e WSL2
- Abrir Ubuntu ou distro
- Instalar docker via linha de comando: https://docs.docker.com/engine/install/ubuntu/
- Iniciar docker: sudo dockerd
- Eu outro terminal rodar container do postgres: https://jkarelins.medium.com/run-postgresql-database-in-docker-container-on-wsl2-656ed3c02280

- Verificar IP do WSL, no powershell 
- wsl --list
- wsl -s distro
- wsl hostname -I
- Test-NetConnection -ComputerName <IP> -Port 5432
