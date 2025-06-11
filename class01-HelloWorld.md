# Class 01: HelloWorld

Projeto .NET do tipo Console.

## Instalação do SDK .NET

Baixe e instale o SDK .NET no site [https://dotnet.microsoft.com/en-us/](https://dotnet.microsoft.com/en-us/)

Verifique a instalação via terminal:

```bash  
    dotnet --version
```

## Projeto "HelloWorld"

- Crie o projeto HelloWorld
Será criado uma pasta HelloWorld e dentro a estrutura básica de uma projeto C# para ser executada no terminal. 

```bash        
    dotnet new console -o HelloWorld
```

- Entre na pasta do projeto
    
```bash
    cd HelloWorld
```

- Execute o projeto com o .NET
    
```bash
    dotnet run
```

Por padrão quando criamos um projeto .NET de console já é criado o arquivo **Program.cs** que é o arquivo principal e n mesmo já possui o código necessário para exibir o texto “Hello World” na tela, então após a execução dos comandos acima veremos o texto “Hello World” sendo impresso no nosso terminal.