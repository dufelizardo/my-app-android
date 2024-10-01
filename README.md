# MY APP - Android

Este projeto faz parte da atividade prática da disciplina de **Teste Mobile** da pós-graduação em Engenharia de Qualidade de Software e Testes Automatizados. O aplicativo **MY APP** é uma aplicação Android criada com o objetivo de praticar e aplicar técnicas de testes automatizados para aplicações móveis.

## Índice
- [Descrição do Projeto](#descrição-do-projeto)
- [Funcionalidades](#funcionalidades)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Testes](#testes)
- [Contribuições](#contribuições)
- [Licença](#licença)

## Descrição do Projeto

O **MY APP** é um aplicativo Android desenvolvido para fins educacionais, com foco no estudo de testes mobile. O objetivo principal do projeto é implementar e executar diferentes tipos de testes automatizados, como testes unitários, testes de interface (UI) e testes de integração.

Este projeto permite:
- Criar casos de teste automatizados para verificar a funcionalidade do app.
- Aplicar conceitos e ferramentas de teste como **JUnit**, **Espresso** e **Mockito**.
- Melhorar a cobertura de testes do aplicativo Android.

## Funcionalidades

As principais funcionalidades do **MY APP** são:
- [Funcionalidade 1] Descrever brevemente a função.
- [Funcionalidade 2] Descrever brevemente a função.
- [Funcionalidade 3] Descrever brevemente a função.

## Requisitos

Para executar e testar o **MY APP**, é necessário ter os seguintes softwares instalados:

- [Android Studio](https://developer.android.com/studio) (versão mais recente)
- **Java** JDK 8 ou superior
- **Gradle** (embutido no Android Studio)
- Dispositivo Android ou emulador para execução e testes

## Instalação

1. Clone este repositório no seu ambiente de desenvolvimento local:
   ```bash
   git clone https://github.com/seuusuario/my-app-android.git
   ```

2. Abra o projeto clonado no **Android Studio**.

3. Aguarde o **Gradle** sincronizar as dependências do projeto.

4. Conecte um dispositivo Android físico ou configure um emulador no **Android Studio**.

5. Execute o projeto diretamente pelo Android Studio, clicando em **Run** ou utilizando o atalho `Shift + F10`.

## Testes

Este projeto inclui uma suíte de testes automatizados, que cobre:
- **Testes Unitários**: Verificação de métodos e funções de forma isolada.
- **Testes de Interface (UI)**: Automação da interação com a interface do usuário, utilizando **Espresso**.
- **Testes de Integração**: Garantem que os diferentes módulos do aplicativo funcionam corretamente em conjunto.

### Executar os testes

1. No **Android Studio**, navegue até a aba de testes no lado esquerdo da interface.
2. Execute os testes de forma individual ou execute todos de uma vez:
   - Para executar os **testes unitários**:
     ```bash
     ./gradlew test
     ```
   - Para executar os **testes de interface (UI)**:
     ```bash
     ./gradlew connectedAndroidTest
     ```

### Ferramentas e Bibliotecas de Teste

O **MY APP** utiliza as seguintes ferramentas e bibliotecas para teste:
- [JUnit](https://junit.org/junit5/): Para criação de testes unitários.
- [Espresso](https://developer.android.com/training/testing/espresso): Para testes de interface.
- [Mockito](https://site.mockito.org/): Para mockar dependências e criar cenários de teste mais isolados.

## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões, correções ou novas ideias para o **MY APP**, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma nova branch:
   ```bash
   git checkout -b feature-nova-funcionalidade
   ```
3. Realize suas modificações e adicione testes para as novas funcionalidades.
4. Envie um Pull Request.

## Licença

Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT). Consulte o arquivo `LICENSE` para mais detalhes.

---
