# password_generator

**Password Generator with File Output**
It generates random passwords with or without special characters, and writes them to a text file.

**Functionality**
The program uses the random module in Python to generate random passwords. The user is prompted to enter the desired length of the password. The program then generates a password consisting of random characters of that length. The characters can be uppercase letters, lowercase letters, numbers, or special characters, depending on the user's choice.

**Usage**
Clone the repository or download the gerador_senha.py file to your computer.
Follow the prompts to choose whether to include special characters in your password and to specify the length of the password.
The generated password will be displayed on the screen.
It will then prompt you to generate another password or exit the program. And the program loops until the user decides to exit the program by pressing continuously 'esc'.
The generated passwords are saved in a text file named senha.txt in the same directory as the program. You can view the passwords by opening the file in any text editor.
The program also writes the current date and time.
Note: if the senha.txt file already exists, the new passwords will be appended to the end of the file.

**Requirements**
bult-in libraries:
*random
*string
*datetime
*os

------------------

**Gerador de Senhas com Saída para Arquivo**
Ele gera senhas aleatórias com ou sem caracteres especiais e as escreve em um arquivo de texto.

**Funcionalidade**
O programa usa o módulo random do Python para gerar senhas aleatórias. O usuário é solicitado a inserir o comprimento desejado da senha. O programa então gera uma senha composta por caracteres aleatórios com esse comprimento. Os caracteres podem ser letras maiúsculas, letras minúsculas, números ou caracteres especiais, dependendo da escolha do usuário.

**Uso**
Clone o repositório ou faça o download do arquivo gerador_senha.py em seu computador.
Siga as instruções para escolher se deseja incluir caracteres especiais em sua senha e especificar o comprimento da senha.
A senha gerada será exibida na tela.
Em seguida, será solicitado que você gere outra senha ou saia do programa. E o programa continua em um loop até que o usuário decida sair do programa pressionando continuamente 'esc'.
As senhas geradas são salvas em um arquivo de texto chamado senha.txt no mesmo diretório do programa. Você pode ver as senhas abrindo o arquivo em qualquer editor de texto.
O programa também escreve a data e hora atual.
Nota: se o arquivo senha.txt já existir, as novas senhas serão anexadas ao final do arquivo.

**Requisitos**
bibliotecas internas:
*random
*string
*datetime
*os
