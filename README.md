# java-print-escada-flexivel

# Variáveis
- **coluna**

    Define o número de colunas que será exibido. É alterado pelo usuário.

- **igualarColuna**

    Usada para testar se a quantidade de colunas exibidas é igual ao número pedido pelo usuário.

- **asterisco**

- **espaco**
- **imagens**

    Usada para definir qual imagem será imprimida no prompt. (O nome poderia ser substituído por algo como "menu".)

- **xquadrado**

    Define o tamanho da imagem (A imagem é sempre um quadrado x*x). 

# Explicação

```java
    System.out.println("Qual o tamanho da imagem?");
    xquadrado = input.nextInt();
```


O código pede ao usuário o tamanho da imagem, um número inteiro que é atribuído a variável **"xquadrado"**.

A variável **"xquadrado"** é usada em todas as estruturas de print que geram as "escadas de asteriscos" para definidir o tamanho da imagem gerada.

A imagem é sempre um quadrado perfeito, por isso nome da variável.


```java
    do{
    }while(imagens != 0);
```


É iniciada a estrutura de repetição. A condição de finalização dessa estrutura é a variável **"imagens"** ser igual a **0**.

Por padrão a variável **"imagens"** tem como valor **"1"**.


```java
        System.out.println("Qual imagem você deseja imprimir?");
        System.out.println("\n\"1 - TODAS.\"" + "\n\"2 - Imagem 1.\"" + "\n\"3 - Imagem 2.\"" + "\n\"4 - Imagem 3.\"" + "\n\"5 - Imagem 4.\"" + "\n\"6 - Imagem 5.\"" + "\n\"0 - Sair.\"");
        imagens = input.nextInt();
```

O código pede ao usuário que escolha se deseja imprimir uma imagem específica ou todas as imagens, um número inteiro que é atribuído a variável **"imagens"**.


```java
        if(imagens > 0 && imagens < 7){
        }
        else if(imagens < 0 || imagens > 6){
            System.out.println("\nOpção inválida!\n");
        }
```


Primeiramente o código valida se o valor de **"imagens"** está entre 1-6, nesse caso o programa progride para o calculo e exibição de todas as imagens ou de uma imagem específica a depender da opção escolhida. Caso o valor de *"imagens"* for menor do que **"0"** ou maior do que **"6"** o sistema exibe uma mensagem de erro e pede ao usuário para digitar o valor da variável novamente.

Em caso do valor da variável ser igual a **"0"** o código não executa nada e para.