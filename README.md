# 🤖 Bot de Resposta Automática para WhatsApp

Este projeto é um bot simples de WhatsApp desenvolvido em **Node.js** utilizando a biblioteca `whatsapp-web.js`.

Ele responde automaticamente mensagens recebidas durante o horário comercial.

---

## 🚀 Funcionalidades

* ✅ Resposta automática de mensagens
* ⏰ Funciona apenas entre **08:00 e 18:00**
* 🛑 Evita spam (responde apenas 1 vez a cada 10 minutos por contato)
* 💬 Mensagem formal profissional
* 🔐 Autenticação via QR Code (WhatsApp Web)

---

## 📌 Mensagem automática

```txt
Olá, agradeço o seu contato.

No momento estou em horário de trabalho e atuo como técnico de atendimento na empresa E&L Produções de Software. Sua mensagem é muito importante e será respondida assim que possível.

Agradeço pela compreensão.

Atenciosamente.
```

---

## 🛠️ Tecnologias utilizadas

* Node.js
* whatsapp-web.js
* qrcode-terminal

---

## ⚙️ Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/bot-do-zap.git
```

### 2. Acesse a pasta

```bash
cd bot-do-zap
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Execute o bot

```bash
node index.js
```

---

## 📱 Conectar ao WhatsApp

* Ao rodar o projeto, será exibido um QR Code no terminal
* Abra o WhatsApp no celular
* Vá em **Dispositivos conectados**
* Clique em **Conectar um dispositivo**
* Escaneie o QR Code

---

## ⚠️ Observações importantes

* O bot funciona como o WhatsApp Web (não é API oficial)
* É necessário manter o projeto rodando para o bot funcionar
* Recomendado usar em ambiente estável (PC ligado e com internet)

---

## 💡 Possíveis melhorias

* Respostas personalizadas por palavra-chave
* Integração com banco de dados
* Sistema de agendamento automático
* Painel administrativo

---

## 📄 Licença

Este projeto é apenas para fins de estudo e uso pessoal.

---

## 👨‍💻 Autor

Desenvolvido por você 🚀
Com apoio de IA para acelerar o desenvolvimento.
