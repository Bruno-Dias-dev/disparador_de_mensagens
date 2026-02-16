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
