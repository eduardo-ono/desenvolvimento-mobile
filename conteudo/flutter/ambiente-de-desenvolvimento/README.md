> ### Desenvolvimento Mobile

# Flutter > Ambiente de Desenvolvimento

Prof. Eduardo Ono

<br>

## Descrição

<br>

Há várias opções de Ambientes de Desenvolvimento para o Flutter:

  1. Android Studio + Flutter SDK
  1. Android Studio + Visual Studio Code + Flutter SDK
  1. DartPad - https://dartpad.dev/flutter?null_safety=true

## Ambiente 1: Android Studio + Flutter SDK

* [x] Instalar o Android Studio com as opções _default_
* [x] Configurar o Android SDK
* [x] Configurar um Emulador Android
* [ ] Instalar os plugins Dart e Flutter no Android Studio
* [ ] Instalar o Flutter SDK

  OBS.: As opções marcadas estão abordadas em [Ambiente de Desenvolvimento](../../02-ambiente-de-desenvolvimento/).


## Ambiente 2: Android Studio + Visual Studio Code + Flutter SDK

* [ ] Instalar e configurar o Android Studio conforme o Ambiente 1
* [ ] Instalar o Visual Studio Code (VS Code)
* [ ] Instalar a extensão Flutter [Dart Code] no VS Code
* [ ] Instalar o Flutter SDK

## Instalando o Flutter SDK

* Site do desenvolvedor:

  https://flutter.dev/docs/get-started/install/windows/

  ### Windows

  * Baixar o arquivo .zip (~700 MB) e descompacar o arquivo em um diretório de sua preferência, por exemplo, `C:\src` ou `C:\`. Será criado um sub-diretório chamado flutter.

    OBS.: **Não** instalar (descompactar) o flutter em um diretório que requer privilégios elevados, por exemplo, `C:\Arquivos de Programas`.

  * Adicionar o diretório `<path>\flutter\bin` na variável de ambiente `Path` do Windows.

  ### Linux (Ubuntu)

  * No Terminal, digitar o comando:

    ```sh
    sudo snap install flutter --classic
    ```

  ### Mac

  |||
  | :-: | --- |
  | ![img](https://img.youtube.com/vi/qt20g3zuVbA/default.jpg) | [Rodrigo Rahman] [__Curso de Flutter - Aula 1 Configurando seu ambiente de desenvolvimento para o flutter__](https://www.youtube.com/watch?v=qt20g3zuVbA) \|\| 44:01, YouTube, Ago/2020.

  <br>

* Para verificar se a instalação do Flutter teve sucesso, digite no Terminal o comando:

  ```
  flutter --version
  ```

* Para verificar se todos os [requisitos para execução do flutter](./figuras/flutter-doctor-erros.png) estão instalados, digitar:

  ```
  flutter doctor
  ```

* Para __atualizar__ o Flutter, abra o Terminal e digite o comando:

  ```
  flutter upgrade
  ```

<br>

## Configurando Variáveis de Ambiente no Windows

* Na janela de pesquisa do Windows, digitar _variáveis_.
  *  Para adicionar uma variável de usuário, escolher a opção 'Editar as variáveis de ambiente para sua conta'.
  *  Para adicionar uma variável de sistema , escolher 'Editar as variáveis de ambiente do sistema'. Também é possível abrir a janela 'Propriedades do Sistema' digitando-se `sysdm.cpl` na janela 'Executar'. Na aba 'Avançado', clicar em 'Variáveis de Ambiente'.
    * Na janela 'Variáveis de Ambiente', clicar em 'Novo' para adicionar uma nova variável ou 'Editar' para editar uma variável já existente (deve estar selecionada).

## Flutter Web

  * [ ] Instalar o navegador Google Chrome
  * [ ] Se necessário, adicionar a variável de ambiente `CHROME_EXECUTABLE`, cujo valor é o executável `path\chrome.exe`:

    <img src="./figuras/chrome-executable-env-var.png" alt="" width="480px">

  ### Configurando Variáveis de Ambiente no Linux/Bash

<br>
