# Automation Wazuh


> Essa integração permite que o usuário envie alertas de e-mail totalmente personalizáveis.
> Esta é uma implementação simples para a qual a mensagem é customizada na função generate_msg(). Um corpo html completo é aceito, se necessário.
> O script pode ser facilmente adaptado para usar autenticação ou um postfix local.
> Conforme explicado no guia a seguir:
> https://documentation.wazuh.com/4.2/user-manual/manager/manual-email-report/smtp-authentication.html

### Configuration example:
```
 <integration>
      <name>custom-email-alerts</name>
      <hook_url>emailrecipient@example.com</hook_url>
      <group>attacks</group>
      <alert_format>json</alert_format>
 </integration>
```

[⬆ Voltar ao topo](#nome-do-projeto)<br>
