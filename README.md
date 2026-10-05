# Calculadora Descontos - xUnit

Projeto desenvolvido em **C# com .NET 10** para praticar testes unitários utilizando o framework **xUnit**.

O principal objetivo da atividade é compreender a diferença entre os atributos `[Fact]` e `[Theory]`.

## Estrutura do Projeto

A solução possui dois projetos:

- `CalculadoraDescontos.App` - contém o código de produção.
- `CalculadoraDescontos.Tests` - contém os testes unitários.

```text
CalculadoraDescontos/
│
├── CalculadoraDescontos.sln
│
├── CalculadoraDescontos.App/
│   ├── CalculadoraDescontos.App.csproj
│   ├── Program.cs
│   └── DescontoService.cs
│
├── CalculadoraDescontos.Tests/
│   ├── CalculadoraDescontos.Tests.csproj
│   └── DescontoServiceTests.cs
│
├── README.md
├── .gitignore
└── LICENSE
