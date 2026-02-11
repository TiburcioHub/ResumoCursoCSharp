# Conectando repositório local com o remoto.
- git remote add origin [URL]
 - git push -u origin main 


# Primeiros comandos em git

| Comandos | O que fazem? |
| :--- | :--- |
| `git init` | Começa a monitor as mudanças na pasta |
| `git status` | Verificar se há mudanças na área de preparação. |
| `git add .` | adicionar mudanças à área de preparação (staging area).. |
| `git commit -m "..."` | Salvar as mudanças da área de preparação |
| `git pull` | traz os commits do GitHub para o seu PC. 📥. |
| `git push` | Envia seus commits locais para o GitHub. 📤 |

# Trabalhando com "Branch" 🌳

 Comandos | O que fazem? |
| :--- | :--- |
| `git checkout -b [nome branch]` | Cria uma nova branch e pula para ela.|
| `git merge [nome branch] ` |Mescla as mudanças da branch X para Y.|
| `git checkout [nome branch] ` |Navegar entre as branch.|
| `git branch [nome branch] ` |Listar branchs.|
| ` branch -d [nome branch] ` |Deletar branch após merge.|



# Dicas de padronização de mensagens
### commit -m "..."

|Tipos | Quando usar| 
|:--- | :---|
|`feat 🚀`| feat: Quando você adiciona uma funcionalidade nova ao projeto.|
|`fix 🛠️`| fix: Quando você conserta um erro (bug) que encontrou.|
|`docs 📚`|docs: Quando você altera apenas a documentação (como o README.md).|
|`style 🎨`| style: "Mudanças que não afetam o código (espaços, formatação, ponto e vírgula)."|
|`refactor ♻️`|refactor :"Uma mudança no código que não corrige erro nem adiciona função, apenas melhora a estrutura."|

