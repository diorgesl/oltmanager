# OltManager

## Descrição

O OltManager é um binário desenvolvido em Go que realiza busca SNMP em equipamentos OLTs da Huawei e também opera como um servidor SNMP Trap. Ele coleta dados diretamente das OLTs, sendo capaz de identificar ONUs conectadas e registrar eventos detectados via traps SNMP. Todos os dados trabalhados localmente são processados pelo próprio binário e enviados conforme necessário para sistemas conectados.

> **Atenção:** Para que o binário opere corretamente, é necessário fornecer um token de autenticação válido.

## Recursos

- Coleta e identificação de ONUs conectadas a OLTs (SNMP Walk).
- Operação autônoma para registrar eventos recebidos via SNMP Traps.
- Verifica métricas de desempenho e status de equipamentos.
- Relatórios detalhados disponíveis via log local.
  
### Funcionalidades:

- Adição/Exclusão de OLTs.;
-Monitoring traps local/ any . 

