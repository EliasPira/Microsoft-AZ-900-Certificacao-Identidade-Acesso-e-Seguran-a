<h1 align="center">🚀 AZ-900 — Identidade, Acesso e Segurança no Microsoft Azure</h1>

<p align="center">
  <img src="https://img.shields.io/badge/AZ--900-Microsoft%20Azure%20Fundamentals-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Ativo-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Contribuições-Bem--vindas-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Licença-MIT-yellow?style=for-the-badge"/>
</p>

<p align="center">
  Material de estudo baseado nos módulos oficiais da Microsoft Learn.<br>
  Ideal para estudantes e desenvolvedores que estão se preparando para a certificação <strong>AZ-900</strong>.
</p>

---

## 📘 Sobre o Repositório

Este repositório reúne conceitos essenciais sobre **Identidade, Acesso e Segurança no Azure**, incluindo:

- Microsoft Entra ID  
- Métodos de autenticação  
- Identidades externas  
- Acesso Condicional  
- RBAC  
- Zero Trust  
- Defesa em profundidade  
- Microsoft Defender para Nuvem  

---

## 🧭 Sumário

- [Serviços de Diretório](#-serviços-de-diretório-no-azure)  
- [Métodos de Autenticação](#-métodos-de-autenticação-no-azure)  
- [Identidades Externas](#-identidades-externas)  
- [Acesso Condicional](#️-acesso-condicional)  
- [RBAC](#-controle-de-acesso-baseado-em-função-rbac)  
- [Zero Trust](#-modelo-de-confiança-zero-zero-trust)  
- [Defesa em Profundidade](#-defesa-em-profundidade)  
- [Microsoft Defender para Nuvem](#-microsoft-defender-para-nuvem)  
- [Links Oficiais](#-links-oficiais-para-estudo)  
- [Para Saber Mais](#-para-saber-mais)  

---

## 🔐 Serviços de Diretório no Azure

### **Microsoft Entra ID**
Serviço de gerenciamento de identidades e acesso baseado em nuvem.

**Principais recursos:**
- Autenticação  
- Logon único (SSO)  
- Gerenciamento de aplicativos  
- Colaboração B2B  

### **Microsoft Entra Domain Services**
- Suporte a LDAP, NTLM e Kerberos  
- Ideal para aplicações legadas  
- Sincronização automática com o Entra ID

---

## 🔑 Métodos de Autenticação no Azure

### **Autenticação**
Identifica quem está tentando acessar um recurso.

### **Autorização**
Define o que o usuário pode fazer após ser autenticado.

### **MFA — Autenticação Multifator**
Requer dois ou mais fatores:
- Algo que você sabe  
- Algo que você possui  
- Algo que você é  

### **SSO — Logon Único**
Acesso a múltiplos aplicativos com uma única autenticação.

### **Autenticação Sem Senha**
- Windows Hello  
- Chaves FIDO2  
- Microsoft Authenticator  

---

## 🌐 Identidades Externas

### **B2B (Business-to-Business)**
- Colaboração com parceiros usando suas próprias credenciais  

### **B2C (Business-to-Consumer)**
- Login com redes sociais, email e outros provedores  

---

## 🛡️ Acesso Condicional

O Acesso Condicional avalia sinais como:
- Usuário ou grupo  
- Localização  
- Dispositivo  
- Aplicativo  
- Risco detectado  

E permite impor:
- MFA - Atenticação Multi Fator
- Bloqueio de acesso  
- Acesso apenas em dispositivos gerenciados  

---

## 👥 Controle de Acesso Baseado em Função (RBAC)

- Permissões granulares  
- Princípio do menor privilégio  
- Controle de acesso ao portal e recursos do Azure  

---

## 🧱 Modelo de Confiança Zero (Zero Trust)

Baseado em três pilares:

1. **Verificar de modo explícito**  
2. **Acesso com privilégios mínimos**  
3. **Tratar a violação como condição prévia**  

---

## 🛡️ Defesa em Profundidade

Modelo de segurança em camadas:
- Segurança física  
- Identidade e acesso  
- Perímetro  
- Rede  
- Computação  
- Aplicativo
- Dados  

---

## 🛡️ Microsoft Defender para Nuvem

Serviço de proteção e monitoramento que oferece:
- Recomendações de segurança  
- Detecção e bloqueio de malware  
- Identificação de ataques  
- Acesso Just-in-Time  

---

## 📎 Links Oficiais para Estudo

- Introdução ao módulo  
  https://learn.microsoft.com/training/modules/describe-azure-identity-access-security/1-introduction

- Métodos de autenticação  
  https://learn.microsoft.com/training/modules/describe-azure-identity-access-security/3-authentication-methods

- Identidades externas  
  https://learn.microsoft.com/training/modules/describe-azure-identity-access-security/4-external-identities

- Modelo Zero Trust  
  https://learn.microsoft.com/training/modules/describe-azure-identity-access-security/7-describe-zero-trust-model

---

## 📚 Para Saber Mais

### Artigos e Comunidade
- DIO Artigos: https://web.dio.me/articles

### Sugestões de aprofundamento
- Cursos da DIO sobre Azure  
- Documentação oficial do Microsoft Entra  
- Livros sobre Zero Trust e IAM  
- Estudos sobre segurança em nuvem  

---

## 🤝 Contribuições

Contribuições são sempre bem-vindas!  
Sinta-se à vontade para abrir uma **issue** ou enviar um **pull request**.

---

## 📝 Licença

Este projeto está sob a licença **MIT**.

---

<p align="center">
  Feito com 💙 para ajudar na sua jornada rumo à certificação AZ-900.
</p>
