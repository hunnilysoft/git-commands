# 📖 Manual Completo de Git

[![Licença: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white)

Manual de referência rápida para comandos Git, desde configuração inicial até fluxos avançados.

## 📦 Pré-requisitos
- Git instalado ([download](https://git-scm.com/downloads))
- Conta no GitHub/GitLab

## 🚀 Começando

### 1. Configuração inicial
```bash
# Identidade
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```
```bash
# Editor preferencial (opcional)
git config --global core.editor "code --wait"
```
### 2. Fluxo básico

```bash
git init
git add .
git commit -m "Primeiro commit"
git remote add origin https://github.com/seu-usuario/repo.git
git push -u origin main
```
### 📚 Índice de Comandos

### 🌐 Dois Métodos de Autenticação
```bash
Método HTTPS (com token)
git remote set-url origin https://SEU_TOKEN@github.com/usuario/repo.git
```
```bash
Método SSH (recomendado)
git remote set-url origin git@github.com:usuario/repo.git
```
### 🛠️ Solução de Problemas
```bash
Erro: "Updates were rejected"
git pull --rebase origin main
git push
```

```bash
Repositório corrompido
git fsck  # Verifica integridade
git gc    # Limpeza
```

📜 Licença
Este trabalho está licenciado sob Creative Commons Attribution-ShareAlike 4.0 International License.
[![Licença: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)


### ✨ Contribuição
- Faça um fork do projeto
- Crie sua branch (git checkout -b feature/novo-topico)
- Commit suas mudanças (git commit -m 'Adiciona tópico sobre X')
- Push para a branch (git push origin feature/novo-topico)
- Abra um Pull Request

### 📬 Contato
Dúvidas? Abra uma issue ou envie um e-mail para contato@hunnilysoft.com.br


### Como usar este template:
```bash
1. Substitua `seu-usuario/repo` pelos seus dados
2. Personalize as seções de contribuição e contato
3. Adicione mais comandos específicos conforme necessário
4. Para licença:
   - Mantenha os badges e links da CC BY-SA 4.0
   - Inclua o arquivo `LICENSE.md` na raiz do repositório

Dica: Use [Shields.io](https://shields.io) para criar badges personalizados!
```
