### Olá devs 👋

Gosto de criar ótimos softwares e ajudar outras pessoas a fazer o mesmo.

## <img width="45" alt="about" src="https://raw.github.com/elizarov/elizarov/master/about.png"> Mais sobre mim

<img align="right" width="300" src="https://i2.wp.com/allhtaccess.info/wp-content/uploads/2018/03/programming.gif?fit=1281%2C716&ssl=1" />

```C#
Desenvolvedor PedroNetto = new(
    nome: "Pedro Netto",
    areaAtuacao: "Desenvolvedor Júnior",
    "C#", ".NET", "SQL Server", "JavaScript", "HTML", "CSS", "Git");

public class Desenvolvedor
{
   
    public string Nome { get; private set; }
    public IReadOnlyCollection<string> Conhecimentos => _conhecimentos;
    public string AreaAtuacao { get; private set; }

    private List<string> _conhecimentos = new();

    public Desenvolvedor(string nome, string areaAtuacao, params string[] conhecimentos)
    {
        this._conhecimentos.AddRange(conhecimentos);
        this.Nome = nome;
        this.AreaAtuacao = areaAtuacao;
    }
}
```
