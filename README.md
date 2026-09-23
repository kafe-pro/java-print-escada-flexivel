# java-print-escada-flexivel

```java
                    // Imagem 2
                    asterisco = 0;
                    espaco = 4;
                    for(int i = 1 ; i <= 4 ; i++){
                        igualarColuna = 0;
                        asterisco = 0;

                        do{
                            if(asterisco < espaco){
                                System.out.print("*");
                                igualarColuna++;
                            }
                            else{
                                System.out.print(" ");
                                igualarColuna++;
                            }

                            asterisco++;

                            if(asterisco >= 4){
                                asterisco = 0;
                            }
                        }while(igualarColuna < coluna);

                        espaco--;
                        System.out.println("");
                    }
                    // Linebreak
                    System.out.println("");
```