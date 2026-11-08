# Solar — site institucional React

Demonstração de site institucional de energia solar, inspirada na referência visual fornecida.

## Iniciar no VS Code

1. Abra a pasta `solar-institucional` no VS Code.
2. Execute `npm install`.
3. Execute `npm run dev`.
4. Abra o endereço local informado pelo Vite.

## Configurar WhatsApp

Copie `.env.example` para `.env` e substitua `VITE_WHATSAPP_NUMBER` pelo número real, incluindo 55 e DDD. Reinicie o servidor após editar.

## Personalização

- Nome demonstrativo: Solar (altere em `src/main.jsx` e `index.html`).
- Cores e layout: `src/styles.css`.
- Fotos: URLs de Unsplash definidas no objeto `photos` em `src/main.jsx`. Requerem conexão com internet. Substitua por fotografias licenciadas e aprovadas pela empresa antes da publicação.
- Formulário: prepara mensagem e abre WhatsApp; não salva dados nem possui backend.
- Textos institucionais: demonstrativos; validar com a empresa antes de publicar.

## Produção

Execute `npm run build` e publique a pasta `dist` em uma hospedagem estática.
