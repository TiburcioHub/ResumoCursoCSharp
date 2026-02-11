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
| `git pull` | Traz os commits feito no repositório remoto. |
| `git push` | Envia os commits realizados no repositório local para o remoto. |

# Trabalhando com "Branch" 🌳

 Comandos | O que fazem? |
| :--- | :--- |
| `git checkout -b [nome branch]` | Cria uma nova branch e pula para ela.|
| `git merge [nome branch] ` |Mescla as mudanças da branch X para Y.|
| `git checkout [nome branch] ` |Navegar entre as branch.|
| `git branch [nome branch] ` |Listar branchs.|
| ` branch -d [nome branch] ` |Deletar branch após merge.|


