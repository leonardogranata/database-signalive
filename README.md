# 📦 Backup do Banco de Dados – Projeto Signalive

Este repositório contém o backup completo do banco de dados do **Signalive**, um projeto essencial que utiliza inteligência artificial para traduzir Libras (Língua Brasileira de Sinais) em tempo real.

---

## 💡 Sobre o Projeto

**Signalive** é uma plataforma que usa visão computacional e aprendizado de máquina para interpretar sinais de Libras captados por uma câmera e traduzi-los automaticamente para o português.

## 🛠️ Como restaurar o banco de dados

Você pode restaurar este backup em um servidor MySQL local ou remoto. Siga os passos:

### Usando o MySQL Workbench

1. Abra o **MySQL Workbench**.
2. Conecte-se ao seu servidor MySQL.
3. Crie um novo schema (ou utilize um já existente).
4. Vá em `File > Open SQL Script`, selecione `arquivo-mais-recente`.
5. Execute o script (botão de raio) para importar as tabelas e os dados.
