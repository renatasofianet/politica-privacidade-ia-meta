# STATUS DOS TOKENS - META API

Data: 14 de Janeiro de 2026 - 02:00 WET

## APLICAÇÃO: n8n messages

**App ID:** 1235860008344400  
**Status:** Live (Produção)  
**Tipo:** Business  
**Business:** renatasofiabarbosa  

---

## 📱 WHATSAPP BUSINESS CLOUD API

**Status:** ⚠️ TOKENS NÃO CRIADOS (apenas temporários disponíveis)

### Informações Disponíveis:
- **Phone Number ID:** 691574034033467
- **WhatsApp Business Account ID:** 597471146730201
- **Test Number:** +1 555 141 2965

### ⚠️ AÇÃO NECESSÁRIA:
1. Gerar **Permanent Access Token** (System User)
2. Configurar permissões:
   - WhatsApp Business Messaging
   - WhatsApp Business Management

**Localização:** WhatsApp → Configuração de API → Generate access token

---

## 📷 INSTAGRAM MESSAGING API

**Status:** ❌ TOKEN NÃO CRIADO

### Informações Disponíveis:
- **Página:** RenataSofia
- **Page ID:** 124339020760012

### ⚠️ AÇÃO NECESSÁRIA:
1. Clicar em "Generate token" na página Instagram
2. Gerar Long-Lived Token

**Localização:** Messenger → Definições do Instagram → Access tokens

---

## 💬 MESSENGER API

**Status:** ⚠️ CONFIGURAÇÃO INCOMPLETA

### Setup Atual:
- ✅ Webhooks: Configurável
- ⚠️ Access Tokens: Não subscrito
- ⚠️ Páginas: Nenhuma página adicionada com token

### ⚠️ AÇÃO NECESSÁRIA:
1. Adicionar páginas (botão "Add subscriptions")
2. Gerar tokens para cada página
3. Configurar webhook subscriptions

**Localização:** Messenger → Definições da Messenger API → Generate access tokens

---

## 📝 RESUMO PARA CONTINUAR AMANHÃ

### Tokens a Criar:

**PRIORIDADE ALTA:**
1. ❌ **WhatsApp Permanent Token** - Essencial para produção
2. ❌ **Instagram Access Token** - Para DMs do Instagram
3. ❌ **Messenger Page Tokens** - Para mensagens do Facebook

### Próximos Passos (em ordem):

#### 1. WhatsApp (15 min)
- Ir a: Business Manager → System Users
- Criar System User
- Atribuir permissões WhatsApp
- Gerar Permanent Token
- Guardar token seguro

#### 2. Instagram (5 min)
- Ir a: Definições do Instagram
- Clicar "Generate token" para página RenataSofia
- Trocar por Long-Lived Token (Graph API Explorer)
- Guardar token

#### 3. Messenger (10 min)
- Adicionar página Facebook
- Gerar token da página
- Configurar webhook subscriptions

#### 4. n8n (10 min)
- Criar credencial: META_WHATSAPP_PULSO
- Criar credencial: META_IG_PULSO
- Criar credencial: META_MESSENGER_PULSO
- Testar envio de mensagem

---

## 🔗 LINKS ÚTEIS

- **Dashboard:** https://developers.facebook.com/apps/1235860008344400/dashboard/
- **WhatsApp API:** https://developers.facebook.com/apps/1235860008344400/whatsapp-business/wa-dev-console/
- **Instagram Settings:** https://developers.facebook.com/apps/1235860008344400/messenger/ig-settings/
- **Messenger API:** https://developers.facebook.com/apps/1235860008344400/messenger/messenger_api_settings/

---

## ⚡ APLICAÇÃO: LeadWize

**App ID:** 1376816290526443  
**Status:** In Development (Não publicado)  

### Use Cases Configurados:
- ✅ Facebook Login
- ✅ Meta Ads Manager

### Por Completar:
- ⭕ Business verification
- ⭕ App Review
- ⭕ Publicação

---

**Notas:**
- NUNCA usar WhatsApp pessoal para API
- Tokens temporários expiram - usar apenas permanentes em produção
- Guardar todos os tokens de forma segura (nunca committar no código)
- Nomear credenciais claramente no n8n
