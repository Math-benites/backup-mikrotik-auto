# backup-mikrotik-auto

Backup .backup e .RSC enviado via email 


## Requisitos

1- Ter um email

2- endereco SMTP E PORTA , login e senha...

## Configuracao Ambiente para o Script

Realize esses comandos antes de adicionar o script , altere conforme necessario

Para Gmail (verifique se seu email nao tem restricao para enviar app de terceiros)
```
/tool e-mail set address=smtp.gmail.com from=SEU@EMAIL.COM password="SENHA" port=587 start-tls=yes user=SEU@EMAIL.COM
```

# EXTRA

Pode ser usado em script > Scheduler

#Creditos
Matheus Benites


https://www.linkedin.com/in/matheus-benites/
