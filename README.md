# VPN Studio — Gestor de configurações JSON

## Como abrir
1. Extrai o ZIP.
2. Abre a pasta no VS Code.
3. Abre `index.html` no navegador. Opcional: usa a extensão Live Server.

Não precisa de Node.js nem de dependências.

## Incluído
- Importação e exportação JSON.
- Editor JSON com formatação e validação.
- Guardar no armazenamento local do navegador.
- Blocos independentes para Servidores, Redes/Payloads e UDP.
- Adicionar, editar, duplicar, eliminar e pesquisar blocos.
- Campos comuns para SSH, SSL/TLS, HTTP Proxy, WebSocket, UDP, V2Ray/Xray, VMess, VLESS, Trojan, Shadowsocks, WireGuard e OpenVPN.
- Campos avançados JSON para preservar propriedades adicionais.
- Configurações gerais: Version, ReleaseNotes, UrlUpdate, Sms, SmsLink, EmailFeedback, UrlContato, UrlTermos e CheckUser.

## Notas
- A aplicação gere ficheiros de configuração; não cria nem testa túneis VPN.
- `SmsLink` é um campo extra. Se a aplicação de destino exigir outro nome de propriedade, altera-o no Editor JSON.
- Confirma que o JSON corresponde ao esquema exigido pela aplicação VPN de destino.
- Remove credenciais sensíveis antes de partilhar ficheiros.
