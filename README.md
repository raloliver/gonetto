# Desenvolvimento web com Go

[LINK](https://www.youtube.com/playlist?list=PL0qudqr7_CuStQUsf2vtHXMxOp5gl_ENc)

## Porque uma nova linguagem?

[Introdução a Go](https://youtu.be/t7k7Ay1U7MQ)

- Go tem um certo pedigree. 
- Muitos problemas com software em larga escala
- Velocidade de compilação
- Semântica simples (por volta de 20 palavras reservadas)
- Geralmente tem apenas uma maneira de fazer as coisas
- Tipagem estática
- Go trabalha com o conceito de pacotes

> Em Go, para uma função ser pública, basta que ela tenha a primeira letra maiúscula

> OO via COMPOSIÇÃO e não herança, biblioteca padrão poderosa, etc.

#### Resultados Múltiplos (8:30)

![Resultados Múltiplos com Sugar Syntax](https://i.imgur.com/3n24ySH.png)

> Ao utilizar `:=` é possível criar e definir o tipo da variável

####  Errors 

![Errors](https://i.imgur.com/KwMSUxM.png)

#### Goroutines

![Goroutines](https://i.imgur.com/cROEwtT.png)

> Use `go` antes de chamar a função, com isso é possível executar mais de um processo ao mesmo tempo (multi-cores)

#### Canais

- Para criar um array de inteiros no Go, utilize a seguinte syntax `[]int{1, 3, 5, 7}`
- Caso queira realizar a soma dos valores, é possível fazer isso com multi-cores porém é necessário um aguardar o resultado do outro, e para isso é necessário criar um **canal**, que é algo como um espaço de memória compartilhado.

![Canais](https://i.imgur.com/O23z4Fm.png)

#### Cross Compilation

- Compilação de programas para determinadas plataformas

![Cross Compilation](https://i.imgur.com/WGTKtPA.png)


#### Quem utiliza Go?

![Go Users](https://i.imgur.com/ZM7bkIy.png)

#### Onde posso utilizar Go?

- APIs
- Microservices
- IoT
- Databases
- Aplicativos CLI
- Serveless

#### Materials de estudo

- golang.org
- gobyexample.com
- https://www.youtube.com/channel/UCxD5EE0H7qOhRr0tIVsOZPQ

