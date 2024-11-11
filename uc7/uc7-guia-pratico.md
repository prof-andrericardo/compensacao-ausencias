# 📘 Guia: Instalando Seu Primeiro Servidor

## 1. Preparação da Máquina Virtual
- Criar VM no Hyper-V
  * 2GB RAM
  * 20GB HD
  * 1 placa de rede

## 2. Instalação do Debian
1. Baixar ISO do Debian
2. Instalar modo básico
3. Configurar rede
4. Atualizar sistema:
```bash
sudo apt update
sudo apt upgrade
```

## 3. Instalando DNS (bind9)
```bash
# Instalar bind9
sudo apt install bind9

# Configurar arquivo principal
sudo nano /etc/bind/named.conf.local

# Exemplo de zona DNS
zone "meuservidor.local" {
    type master;
    file "/etc/bind/db.meuservidor";
};

# Testar configuração
sudo named-checkconf
```

## 4. Instalando Web (nginx)
```bash
# Instalar nginx
sudo apt install nginx

# Criar página web simples
sudo nano /var/www/html/index.html

# Exemplo de página
<html>
<head>
    <title>Meu Servidor Web</title>
</head>
<body>
    <h1>Bem-vindo ao meu servidor!</h1>
    <p>Esta é minha primeira página.</p>
</body>
</html>
```

## 5. Testando os Serviços
```bash
# Testar DNS
nslookup meuservidor.local

# Testar nginx
curl http://localhost
```

## ✅ Checklist de Tarefas
1. [ ] VM criada e configurada
2. [ ] Debian instalado
3. [ ] Sistema atualizado
4. [ ] DNS instalado e funcionando
5. [ ] Nginx instalado e funcionando
6. [ ] Página web criada
7. [ ] Testes realizados
8. [ ] Documentação feita

## 🔍 Comandos Úteis
```bash
# Ver status dos serviços
sudo systemctl status bind9
sudo systemctl status nginx

# Ver logs
sudo tail /var/log/syslog
sudo tail /var/log/nginx/error.log

# Reiniciar serviços
sudo systemctl restart bind9
sudo systemctl restart nginx
```

## 📝 Dicas de Documentação
- Anotar cada comando usado
- Tirar screenshot de cada etapa
- Documentar erros encontrados
- Registrar como resolveu problemas

Esta versão está mais simples e focada, adequada para iniciantes em Linux. Quer que eu ajuste ou detalhe melhor alguma parte?