# Análise das Entradas do Diário do Sistema com journalctl

Este repositório foi criado para ajudar usuários a localizar e interpretar entradas no diário do sistema usando o comando `journalctl` no Linux. Com isso, é possível solucionar problemas, revisar o status do sistema e otimizar o uso do `systemd-journald`.

## Como usar o journalctl

O `journalctl` permite visualizar mensagens de log do sistema em tempo real, aplicar filtros por prioridade, procurar por eventos específicos e muito mais.

### Exemplos de comandos úteis

1.  **Visualizar todas as mensagens do diário:**
    
    `journalctl` 
    
2.  **Filtrar mensagens por prioridade (erro e acima):**
    
    
    `journalctl -p err` 
    
3.  **Monitorar o diário em tempo real:**
    
    
    `journalctl -f` 
    
4.  **Visualizar logs de uma unidade específica (exemplo: sshd):**
    
    
    `journalctl -u sshd.service` 
    

