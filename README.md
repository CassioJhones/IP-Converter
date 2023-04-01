# IP-Converter
Conversor de IPV4 para IPV6
Criado para aula de Redes de computadores utilizando linguagem Python
> FHO - Uniararas - 2019

![Screenshot_2](https://user-images.githubusercontent.com/56178855/76355212-a0f15680-62f2-11ea-9170-8f99f1ea6bbc.jpg)

Esse código Python implementa uma aplicação gráfica usando o pacote ``tkinter`` que permite ao usuário inserir um endereço IPv4 e convertê-lo em um endereço IPv6.

A aplicação consiste em uma janela principal com três contêineres (dois Frames e um Button) que organizam os widgets na tela. O primeiro contêiner contém um título e os outros dois contêineres contêm um ``Entry (para inserir o endereço IPv4)`` e um ``Button (para converter o endereço)``, respectivamente. Quando o usuário clica no botão "CONVERTER", o método ``converteIPV4()`` é chamado e o endereço IPv4 inserido pelo usuário é convertido em um endereço IPv6 e exibido na tela. O endereço IPv6 gerado é um endereço de túnel IPv6 que representa o endereço IPv4 inserido pelo usuário.

O módulo ``ipaddress`` é usado para realizar a conversão de IPv4 para IPv6. O código tenta criar um objeto IPv6Address do módulo ipaddress concatenando o endereço IPv4 com o prefixo '2002::'. Se a criação do objeto IPv6Address for bem-sucedida, o endereço IPv6 é exibido na tela. Caso contrário, uma mensagem de erro é exibida.

## Autoria
- Cássio Jhones
- Sandro Junior
