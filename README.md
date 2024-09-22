# resumo-do-lab6
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
Contas de armazenamento<br>
<br>
- Ter nome EXCLUSIVO(3 A 24 letra min/num)
- Fornecer acesso a internet em todo mundo
- Standard ou Premium (baixa latencia)
<br>

Determinar os serviços de armazenamento e redundancia:
- LRS (1DT local) 11 noves 3 copias
- ZRS (3DT zona)	12 noves 3 copias
- GRS (1local/1par)16 noves2 copias 
- GZRS(3local/1par)16 noves4 copias

Serviços de armazenamento:<br>
<br>
- Blob dados não estruturados ou dados binarios <blob.core>
- Discos para VM 
- Fila para armazenamento de mensagens <queue.core>
- Files/Arquivo compartilhamento de arquivos de Rede <file.core>
- Tabelas armazenamento de dados estruturados <table.core>
<br>
Camadas de Acesso:<br>
- Frequente acessado frequentemente
- Esporádico pelo menos 30 dias
- Frio acessdo raramente pelo menos 90 dias
- Arquivo Morto acessado raramente 180 dias
<br>
Migrações para o Azure:<br>
- Azure Data Box 40TB a 80TB
- AzCopy utilitario CLI, Unidirecional
- Gerenciador de Armazenamento Interface grafica
- Sincronização de Arquivos arquivos local/remoto, bidireional
