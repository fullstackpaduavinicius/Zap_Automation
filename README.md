# WhatsSender  

Automatize o envio de mensagens individuais e em massa via WhatsApp Web com praticidade e segurança.  

## 📋 Descrição  

**WhatsSender** é uma aplicação desenvolvida em Python que permite o envio automatizado de mensagens no WhatsApp Web. Com uma interface simplificada e funcionalidades robustas, o sistema facilita o envio de mensagens personalizadas para uma lista de números, respeitando limites de tempo para evitar que o WhatsApp interprete como spam.  

## ⚙️ Funcionalidades  

- **Interface simplificada**: Uso intuitivo para qualquer nível de usuário.  
- **Envio automatizado**: Cadastro de números e mensagens com controle de tempo entre os envios.  
- **Suporte a mensagens longas**: Envio de mensagens com mais de 1000 caracteres.  
- **Integração com WhatsApp Web**: Requer confirmação por QR Code apenas uma vez por sessão de envio.  
- **Configuração de tempo entre mensagens**: Personalize o intervalo entre os envios para evitar restrições.  
- **Recomendações de uso**:  
  - Cadastrar até **50 números por vez**.  
  - Configurar o intervalo de envio para **60 segundos**.  
  - Usar uma conta ativa no WhatsApp há alguns meses.  

## 🚀 Como Usar  

1. **Configuração Inicial**  
   - Certifique-se de ter o Python instalado em sua máquina.  
   - Clone este repositório:  
     ```bash
     git clone https://github.com/seu-usuario/WhatsSender.git
     cd WhatsSender
     ```  
   - Instale as dependências necessárias:  
     ```bash
     pip install -r requirements.txt
     ```  

2. **Cadastro de Dados**  
   - Abra o programa e insira:  
     - A lista de números para os quais deseja enviar mensagens.  
     - A mensagem que deseja enviar (limite de caracteres superior a 1000).  
     - O intervalo de tempo entre os envios (recomenda-se 60 segundos).  

3. **Conexão com WhatsApp Web**  
   - Escaneie o QR Code exibido para conectar sua conta do WhatsApp.  
   - Após a conexão, o programa executará o envio automaticamente.  
   - Ao término do processo, será necessário escanear o QR Code novamente para uma nova sessão.  

4. **Dicas para Uso Seguro**  
   - Use contas que estejam ativas há alguns meses para reduzir o risco de bloqueios.  
   - Envie mensagens em lotes de até 50 números para maior segurança.  

## 🛠 Tecnologias  

- **Linguagem**: Python  
- **Interface**: Interface gráfica simplificada  
- **Automação**: Integração com o WhatsApp Web  

## ⚠️ Avisos  

- Este programa deve ser usado com responsabilidade e em conformidade com as políticas de uso do WhatsApp.  
- Evite práticas que possam ser interpretadas como spam para proteger sua conta.  

## 📝 Licença  

Este projeto é de uso pessoal e experimental. Verifique as restrições de uso do WhatsApp antes de utilizá-lo comercialmente.  

---  

**Contribuições e feedback são bem-vindos!**  
