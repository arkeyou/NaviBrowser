Ajuda

```json
{
  "urlMonitor": "URL da página ou serviço que o NAVI deve consultar periodicamente para identificar
   novas informações ou eventos. Exemplo: https://exemplo.com/api/novos-itens",

  "triggerMonitor": "Padrão Regex utilizado para identificar no conteúdo monitorado.
   Exemplo: [A-Z]{3}[0-9]{4} para identificar códigos como ABC1234.",

  "urlAction": "URL da página que o NAVI vai acessar quando o evento monitorado for identificado.
   Exemplo: https://exemplo.com/produto/",

  "mainVerify": {
    "type": "Tipo de verificação realizada na página antes da ação.
     Os tipos válidos são: \"exists\", \"confirm\" ou \"click\".",

    "selector": "Seletor CSS utilizado para localizar o elemento na tela.
     Exemplo: div[class='produto-titulo']. Válido para \"exists\" ou \"click\".",

    "message": "Mensagem exibida no alerta de confirmação. Válido para \"confirm\"."
  },

  "mainAction": {
    "type": "Ação que o NAVI vai realizar quando a condição for atendida.
     Os tipos válidos são: \"exists\", \"confirm\" ou \"click\".",

    "selector": "Seletor CSS utilizado para localizar o elemento na tela.
     Exemplo: div[class='produto-titulo']. Válido para \"exists\" ou \"click\".",

    "message": "Mensagem exibida no alerta de confirmação.
     Válido para \"confirm\"."
  }
}
```
