# OltManager

## Descrição

O OltManager é um binário desenvolvido em Go que realiza busca SNMP em equipamentos OLTs da Huawei (em breve terá para outras OLTs) e também opera como um servidor SNMP Trap. Ele coleta dados diretamente das OLTs, sendo capaz de identificar ONUs conectadas e registrar eventos detectados via traps SNMP. Todos os dados trabalhados localmente são processados pelo próprio binário e enviados conforme necessário para sistemas conectados.

> **Atenção:** Para que o binário opere corretamente, é necessário fornecer um token de autenticação válido.

## Recursos

- Coleta e identificação de ONUs conectadas a OLTs (SNMP Walk).
- Operação autônoma para registrar eventos recebidos via SNMP Traps.
- Verifica métricas de desempenho e status de equipamentos.
- Relatórios detalhados disponíveis via log local.
- Envia alertas em tempo real para um grupo do WhatsApp.
- Alertas individuais por ONT.
- Alertas Massivos instantâneos.
- Métricas de Sinal de cada ONT
  
### Funcionalidades:

- Você pode adicionar/remover as OLTs via CLI
- Você pode listar as OLTs/ONTs
- Servidor SNMP Trap

### TOKEN e WhatsApp

- O Oltmanager precisa de um TOKEN para funcionar, e você pode conseguir entrando em contato.
- O WhatsApp é uma integração que podemos fazer, você adiciona em um grupo nosso contato, e ele automaticamente envia os alertas para esse grupo.
