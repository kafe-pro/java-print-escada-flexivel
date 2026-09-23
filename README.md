# java-print-escada-flexivel

# Variáveis
- **coluna**
    Define o número de colunas que será exibido. É alterado pelo usuário.
- **igualarColuna**
    Usada para testar se a quantidade de colunas exibidas é igual ao número pedido pelo usuário.
- **asterisco**

- **espaco**
- **imagens**
- **xquadrado**
    Define o tamanho da imagem (A imagem é sempre um quadrado x*x). 


# Explicação
    O código pede ao usuário o tamanho da imagem, um número inteiro que é atribuído a variável "xquadrado".
```java
    System.out.println("Qual o tamanho da imagem?");
    xquadrado = input.nextInt();
```

    O código pede ao usuário que escolha se deseja imprimir uma imagem específica ou todas as imagens, um número inteiro que é atribuído a variável "imagens".
```java
    do{
        System.out.println("Qual imagem você deseja imprimir?");
        System.out.println("\n\"1 - TODAS.\"" + "\n\"2 - Imagem 1.\"" + "\n\"3 - Imagem 2.\"" + "\n\"4 - Imagem 3.\"" + "\n\"5 - Imagem 4.\"" + "\n\"6 - Imagem 5.\"" + "\n\"0 - Sair.\"");
        imagens = input.nextInt();
```