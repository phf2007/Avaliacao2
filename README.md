# Avaliação 2

> Um aplicativo Android simples que calcula o salário líquido.

## 📱 Descrição

A **Avaliação 2** permite ao usuário calcular seu salário líquido usando informações como: Salário bruto e Número de fihos.

## 🔧 Funcionalidades

- [x] 1 Tela que fará toda a conta
- [x] Um TextView abaixo do botão que exibe o resultado
- [x] Fácil de entender
- [x] Interface simples e intuitiva
- [ ] Tema claro e escuro (planejado para futuras versões)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **Button**, **EditText** e **RadioButton**

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:


1. Clone este repositório:
    ```bash
    git clone https://github.com/phf2007/Calculadora/primeiroApp.zip
    ```

2. Abra o projeto no Android Studio.

3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

Avaliao2
├── app
│   ├── main
│   │   ├── java/com.example.avaliao2
│   │   │   ├── MainActivity.java                  # Atividade principal onde está elaborado as fórmulas
│   │   ├── res
│   │   │   ├── layout
│   │   │   │   ├── activity_main.xml              # Layout da tela principal
│   │   │   └── values
│   │   │       ├── strings.xml                    # Strings usadas no app
│   │   │       ├── colors.xml                     # Cores definidas no projeto
│   └── build.gradle                               # Configuração do Gradle
└── README.md                                      # Este arquivo



## 🎨 Design e Prototipagem 

A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela. 

O design é minimalista e fácil de usar, com foco na simplicidade.

 ## 🖥️ Telas do Aplicativo

**Tela Principal** 

Na tela principal, teremos EditText de nome e de salário além de RadioButton num RadioGroup que denomina seu sexo, as contas são feitas com INSS, IR e até Salário-Família, pra no final, podermos calcular seu salário líquido.

## 👨‍💻 Desenvolvedores – 
Pedro Henrique Fontes - Desenvolvedor - [GitHub](https://github.com/phf2007)
