# 🧪 Teste Técnico – Vaga Suporte / Infra / DevOps

Seja bem-vindo(a)!

Este é o teste técnico para a vaga de **Suporte / Infraestrutura / DevOps**. A proposta é avaliar seus conhecimentos práticos e teóricos de forma objetiva, cobrindo tópicos como automação, containers, segurança, suporte, versionamento e organização pessoal.

---

## 📦 Formato de Entrega

Você deve entregar:

- ✅ Um **arquivo PDF** contendo:
  - Respostas teóricas
  - Scripts e configurações utilizadas
  - Prints (se necessário)
- ✅ Um **link para o repositório público** (GitHub, GitLab etc.), com:
  - Código-fonte e arquivos utilizados no teste
  - Estrutura organizada em pastas
  - Instruções de execução no `README.md`

---

## ✅ Infraestrutura e Suporte (DevOps)

### 🔧 Instalação e Acesso Remoto

1. Descreva como você faria a **instalação remota do agente do ManageEngine Endpoint Central** em uma máquina com Windows.

2. Explique o que fazem os seguintes comandos em um terminal Linux:

   ```bash
   curl -sSL https://get.docker.com | sh
   systemctl enable docker

## 🐳 Containers e Orquestração

### 1. Crie um `Dockerfile` para uma aplicação Node.js simples.

### 2. Crie um `docker-compose.yml` com os seguintes serviços:

- Aplicação Node.js
- Banco de dados PostgreSQL
- Nginx atuando como reverse proxy para a aplicação

### 3. (Bônus) Explique como você faria o deploy dessa stack em um cluster Kubernetes.

---

## 📈 Observabilidade e Logs

Explique como você configuraria os **logs de um container Nginx** para serem monitorados via **Wazuh**.

Sua explicação deve incluir:

- Quais ajustes devem ser feitos no container
- Como realizar a integração com o agente Wazuh
- Um exemplo de regra ou configuração para identificar eventos relevantes

---

## 🐚 Shell Script

Escreva um **shell script** que execute as seguintes tarefas:

- Verifique se o Docker está instalado na máquina
- Crie um backup de um volume Docker específico
- Envie esse backup via `scp` para um servidor remoto (por exemplo: `backup@192.168.0.100`)


## 💼 Microsoft 365 – Diagnóstico e Suporte

Responda às seguintes situações com base na sua experiência ou lógica de troubleshooting:

1. Um usuário relata que **não consegue enviar e-mails pelo Outlook**.  
   - Quais seriam os **primeiros passos para diagnosticar** o problema?

2. Como você **identificaria e corrigiria problemas de login** no portal do **Microsoft 365**?

3. Um **arquivo compartilhado no OneDrive** não está abrindo para um **colaborador externo**.  
   - O que você verificaria?

4. Um grupo do **Microsoft Teams parou de exibir mensagens**.  
   - Como você investigaria isso?

5. Um usuário reportou que **não recebeu um e-mail específico**.  
   - Como você faria para resolver a situação ou para identificar o problema?

---

## 🧩 Suporte Técnico – Diagnóstico de Sistemas e Rede

Responda de forma objetiva e técnica às situações abaixo:

1. Um **computador com Windows** está apresentando **lentidão**.  
   - Como você faria para **identificar a raiz do problema**?

2. Um **servidor Linux** está apresentando **lentidão**.  
   - Quais comandos você executaria para identificar os processos que estão em execução?  
   - Qual seria o **próximo passo** para diagnosticar e resolver a causa do problema?

3. O ambiente de rede está apresentando **instabilidade intermitente**.  
   - Quais **comandos e ferramentas** você utilizaria para **detectar e analisar** o problema?
