# Brasil Export Mobile
> O projeto Brasil Export mobile, é dividido em dois aplicativos. `Brasil Export` e `BE News`.

## Sobre o Brasil Export
O aplicativo `brasil_export_app` facilita a gestão de atividades e a comunicação entre conselheiros, patrocinadores, autoridades e o público em geral interessado no universo da logística e da infraestrutura portuária.

## Versões
- Flutter 2.10.5
> Após fazer o clone do projeto, é recomendado executar os comandos `flutter clean` e depois `flutter pub get`.

## Tecnologias usadas
- Flutter
- Dart
- Firebase (messaging e database)
- ValueNotifier (gerenciamento de estados)


## Funcionalidades
- Autenticação e login de usuários.
- Visualização de notícias(notas) sobre portos, logística e infraestruturas.
- Calendário com eventos/palestras, que o usuário pode se inscrever de forma online ou presencial.
- Chat One-One entre os usuários cadastrados no aplicativo.
- Configurações do usuário (nome, cargo, empresa, etc).
- Logout e encerramento de conta.

## 
![print](https://user-images.githubusercontent.com/98099163/209825464-e7c70fe9-0f4a-42b0-84e3-fc2f27a9d8fd.png)

## Estrutura do projeto
O Brasil Export é separado em duas pastas (Core e Modules).
> Core

Responsável pela lógica do aplicativo, ela traz todos os widgets, que serão usadas mais de uma vez. Além de armazenar rotas de api's, 
cores, textos e estilos do app. Ela também possui as configurações do firebase, validações e algumas regras de negócio.

> Modules

Os módulos é onde fica toda a parte visual do aplicativo, juntamente com as models e controllers. Todas as telas/funcionalidades são encontradas 
no module.

![brasil-export](https://user-images.githubusercontent.com/98099163/209827691-00e36b20-4842-4f50-b390-ca8a52bc59be.png)

> O projeto usa na sua estrutura o Flutter Modular, responsável por ter uma estrutura de micro frontends (microapps) onde conseguimos separar nosso aplicativo em módulos. Ele também é usado nas rotas do app, no qual trabalhamos com a injecção de dependências.

## Usando o aplicativo

## Intro
Quando o usuário baixa o aplicativo, ele tem como primeiro contato a tela de `Intro`, separado em três telas(beaches), que são 
telas de apresentações, mostrando o que é o Brasil Export e o Portal Be News.
A pasta de `intro` é composta por uma pasta `presenter`, contento uma pasta `controller` e uma de apresentação (`pages`) que possui uma de `widgets`.

![intro](https://user-images.githubusercontent.com/98099163/209830388-1023ee67-71b6-47f9-b8f7-dce3df07db60.png)


## Dashboard
O aplicativo é dividido em quatro telas principais, sendo notas, calendário, chat e configurações.

![dashboard](https://user-images.githubusercontent.com/98099163/209826475-dac86982-0e16-4b07-af8a-1a9c8eb990f5.png)


## Usage
How does one go about using it?
Provide various use cases and code examples here.

`write-your-code-here`


## Project Status
Project is: _in progress_ / _complete_ / _no longer being worked on_. If you are no longer working on it, provide reasons why.


## Room for Improvement
Include areas you believe need improvement / could be improved. Also add TODOs for future development.

Room for improvement:
- Improvement to be done 1
- Improvement to be done 2

To do:
- Feature to be added 1
- Feature to be added 2


## Acknowledgements
Give credit here.
- This project was inspired by...
- This project was based on [this tutorial](https://www.example.com).
- Many thanks to...


## Contact
Created by [@flynerdpl](https://www.flynerd.pl/) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
