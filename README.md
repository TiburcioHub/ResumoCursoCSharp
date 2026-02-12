# Esse repositório tem por objetivo trazer os principais comandos utlizados e apresentados no curso da Eli de git & github


# Conectando repositório local com o remoto. 🔁
- `git remote add origin [URL]` - Conecta a pasta local com o repositório remoto.
 - `git push -u origin main ` - Isso cria uma conexão permanente entre a sua branch local main e a branch main lá no origin (GitHub). 🔗

## ⌨ Comandos diários
- `git status`: Ver o que mudou.
- `git add .`: Preparar tudo para o commit.
- `git commit -m "tipo: descrição"`: Salvar as alterações.
- `git push`: Enviar para o GitHub.
- `git pull`: Trazer novidades do GitHub.
- `git init`: Inicia monitoramento  do git no diretório.

## 🌿 Gerenciando Branches
- `git branch`: Ver em qual "galho" estou.
- `git checkout -b nome`: Criar e entrar num novo galho.
- `git checkout nome`: Pular para um galho existente.
- `git merge nome`: Trazer mudanças de um galho para o atual.

## 🆘 Comandos de Emergência
- `git reset --soft HEAD~1`: Desfazer o último commit (mantendo os arquivos).
- `git remote -v`: Verificar se estou conectado ao repositório certo.
- `git log --oneline`: Ver o histórico de forma simplificada.

# Dicas de padronização de mensagens
### commit -m "..."

|Tipos | Quando usar| 
|:--- | :---|
|`feat 🚀`| feat: Quando você adiciona uma funcionalidade nova ao projeto.|
|`fix 🛠️`| fix: Quando você conserta um erro (bug) que encontrou.|
|`docs 📚`|docs: Quando você altera apenas a documentação (como o README.md).|
|`style 🎨`| style: "Mudanças que não afetam o código (espaços, formatação, ponto e vírgula)."|
|`refactor ♻️`|refactor :"Uma mudança no código que não corrige erro nem adiciona função, apenas melhora a estrutura."|

