🚀 Disparador de Mensagens WhatsApp com n8n

Sistema de disparo de mensagens via WhatsApp utilizando n8n, com suporte a:

✅ Envio de texto
🖼️ Envio de imagem com legenda
⏰ Agendamento de mensagens
📊 Barra de progresso em tempo real
🔗 Integração com Evolution API
🌐 Interface Web personalizada via Webhook
🧠 Arquitetura

Frontend (HTML + Bootstrap)
        ↓
Webhook (n8n)
        ↓
Processamento:
  - Extração de imagem
  - Upload para imgbb
  - Cálculo de delay (Python)
        ↓
Envio:
  - Texto → Evolution API
  - Imagem → Evolution API

🛠️ Tecnologias Utilizadas
n8n
Webhooks
HTML + Bootstrap 5
JavaScript
Python (Node Code)
Evolution API
imgbb API

Possíveis Melhorias Futuras
📄 Importar lista via CSV
📊 Dashboard de métricas
🔐 Autenticação na interface
🗂️ Registro em banco de dados
🧠 Personalização de mensagem (ex: {{nome}})
