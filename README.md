# Heranca-Polimorfismo-Exercicio

Exercício do curso "**C# COMPLETO Programação Orientada a Objetos + Projetos**" pela Udemy, com o professor **Nélio Alves**:

> Fazer um programa para ler os dados de N
produtos (N fornecido pelo usuário).
>Ao final,
mostrar a etiqueta de preço de cada produto na
mesma ordem em que foram digitados.
>Todo produto possui nome e preço. Produtos
importados possuem uma taxa de alfândega, e
produtos usados possuem data de fabricação.
>Estes dados específicos devem ser
acrescentados na etiqueta de preço conforme
exemplo (próxima página).
>Para produtos
importados, a taxa e alfândega deve ser
acrescentada ao preço final do produto.

![Diagrama UML com as classes "Product", "ImportedProduct" e "UsedProduct"](https://live.staticflickr.com/65535/53415051472_38f4b9026b_w.jpg)

Resultado obtido com o Program.cs

    Enter the number of products: 3
    Product #1 data:
    Common, used or imported (c/u/i)? i
    Name: Tablet
    Price: 260.00
    Customs fee: 20.00
    Product #2 data:
    Common, used or imported (c/u/i)? c
    Name: Notebook
    Price: 1100.00
    Product #3 data:
    Common, used or imported (c/u/i)? u
    Name: Iphone
    Price: 400.00
    Manufacture date (DD/MM/YYYY): 15/03/2017
    PRICE TAGS:
    Tablet $ 280.00 (Customs fee: $ 20.00)
    Notebook $ 1100.00
    Iphone (used) $ 400.00 (Manufacture date: 15/03/2017)

---
Ferramentas utilizadas: 
<p align="left">
<a href="https://learn.microsoft.com/pt-br/dotnet/csharp/tour-of-csharp/" target="_blank" rel="noreferrer"> <img src="https://github.com/devicons/devicon/blob/master/icons/csharp/csharp-original.svg" alt="C#" width="40" height="40"/> </a> 
<a href="https://dotnet.microsoft.com/pt-br/" target="_blank" rel="noreferrer"> <img src="https://github.com/devicons/devicon/blob/master/icons/dotnetcore/dotnetcore-original.svg" alt="dotnet" width="40" height="40"/> </a> 
 <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a>
