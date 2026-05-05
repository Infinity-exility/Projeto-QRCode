🧾 Descrição do Projeto

Neste projeto, eu desenvolvi uma aplicação que permite gerar senhas aleatórias seguras, com base em critérios definidos pelo usuário.

O sistema funciona de forma interativa, onde o usuário pode escolher gerar uma senha. A partir disso, o programa monta a senha automaticamente usando diferentes tipos de caracteres, como:

letras maiúsculas
letras minúsculas
números
caracteres especiais

Essas opções são controladas por variáveis de ambiente, o que permite personalizar facilmente o tipo de senha que será gerada. No final, o sistema exibe a senha criada no terminal.

📚 Conceitos que eu utilizei

💻 Programação em JavaScript

Neste projeto, eu utilizei JavaScript com organização em múltiplos arquivos, separando as responsabilidades em diferentes módulos e utilizando import e export para conectar tudo.


🧠 Lógica de Programação

Eu apliquei lógica para:

montar dinamicamente a lista de caracteres permitidos
gerar a senha de forma aleatória
controlar o fluxo do programa com base na escolha do usuário

Também utilizei estruturas de repetição (for) para construir a senha caractere por caractere.

🔐 Geração de Senhas (Segurança Básica)

Implementei um sistema de geração de senha baseado em aleatoriedade, garantindo que:

os caracteres são escolhidos de forma aleatória
a senha pode ter diferentes níveis de complexidade
o tamanho da senha pode ser configurado


🎲 Aleatoriedade

Utilizei Math.random() para selecionar caracteres aleatórios da lista de permitidos, garantindo que cada senha gerada seja diferente.


⚙️ Variáveis de Ambiente

Utilizei process.env para definir:

o tamanho da senha (PASSWORD_LENGTH)
quais tipos de caracteres são permitidos

Isso permite configurar o comportamento do sistema sem alterar o código diretamente.


🧱 Estruturas de Dados (Arrays e Strings)

Utilizei:

arrays para armazenar os caracteres permitidos
strings para construir a senha final


📦 Modularização do Código

Organizei o projeto em diferentes arquivos, cada um com uma responsabilidade:

um módulo para definir os caracteres permitidos
um módulo para gerar a senha
um módulo para controlar a criação
um arquivo principal para iniciar o sistema


🖥️ Interação com o Usuário

Utilizei a biblioteca prompt para permitir que o usuário escolha qual funcionalidade deseja executar, tornando o programa interativo.


🎨 Saída de Dados no Terminal

Utilizei a biblioteca chalk para estilizar a saída no terminal, deixando o texto mais visual e organizado.
