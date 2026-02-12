# Conceitos sobre C#

---

| Termo | Explicação | Exemplo de Código |
| :--- | :--- | :--- |
| **Namespace** | Organiza as classes em grupos lógicos. | `namespace Sintaxe.Models` |
| **Classes** | Representação de um objeto real (o molde). | `public class Pessoa { ... }` |
| **Atributo** | Variáveis que guardam características (propriedades). | `public string Nome { get; set; }` |
| **Método** | Ações ou funções que definem o comportamento. | `public void Apresentar() { ... }` |
| **Objeto** | Representação física da classe em memória. | `Pessoa p = new Pessoa();` |

---

### Exemplo de Implementação
Baseado no código da classe `Pessoa`:

```csharp
// Definindo a Classe e seus Atributos
public class Pessoa 
{
    public string Nome { get; set; }
    public int Idade { get; set; }

    // Definindo um Método
    public void Apresentar() 
    {
        Console.WriteLine($"Olá, meu nome é {Nome} e tenho {Idade} anos.");
    }
}
