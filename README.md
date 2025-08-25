# Azure

## Criação de Banco de dados SQL

É um serviço PaaS (Plataforma como serviço), ou seja, a infraestrutura (IaaS) é gerenciada pela Microsoft e você se preocupa com a criação do banco.

- Etapas 

1. Crie uma conta no Microsoft Azure

2. Criar servidor lógico: Portal → SQL servers → Create:

- O qual deve definir: Server name, Region, Admin login e Password.

3. Criação do banco de dados:
- Você decidde nome do banco de dados e seleciona o servidor.

    - Defina qual é o modelo de redundancia do armazenamento de backup, podendo escolher entre armazenamento de backup com redundancia local, de zona ou geográfica.

        Diferenças:
        - Armazenamento Redundante Local - 
        É mais barato, protege contra falhas locais mas não contra regionais e é copiado três vezes no mesmo datacenter

        - Armazenamento Redundante Zona - 
        Tem um custo intermediário,é copiado em 3 datacenter diferentes e isso garante que mesmo se um datacenter inteiro cair, os outros ainda tem os dados salvos.

        - Armazenamento Redundante geográfico - 
        O mais caro, os dados são armazenados em duas regiões diferente e é recomendado para sistemas que não podem perder dados independente da situação.
        


(Só com isso ele já da qual seria a previsão de custo e é possivel criar um banco de dados SQL)
