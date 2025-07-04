# Desafio de projeto sobre Git/GitHub da Dio
Repositório criado para o Desafio de projeto.

# 🧠 Git Básico + Publicação no GitHub

## 📁 1. Inicializar um repositório Git
```
git init
```
## ➕ 2. Adicionar arquivos ao controle de versão
```
git add nome_do_arquivo
```
# ou para adicionar tudo:
```
git add .
```
## 💬 3. Criar um commit (salvar uma versão)
```
git commit -m "Mensagem descritiva do commit"
```
## 🔗 4. Conectar ao repositório remoto no GitHub
```
git remote add origin https://github.com/usuario/repositorio.git
```
## 📤 5. Enviar os arquivos para o GitHub
### Primeira vez:
```
git branch -M main
git push -u origin main
```
### Próximas vezes:
```
git push
```
## 🔄 6. Clonar um repositório existente do GitHub
```
git clone https://github.com/usuario/repositorio.git
```
## 📥 7. Atualizar o repositório local com mudanças do GitHub
```
git pull
```
## 🧪 Dica extra: Verificar o status e o histórico
```
git status   # Mostra mudanças não adicionadas
git log      # Mostra o histórico de commits
```


## Links úteis
- [Guia Markdown](https://www.markdownguide.org/basic-syntax/)
- [Git](introducao_git_github/anotacoes.md)