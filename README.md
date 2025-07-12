# 🎯 Jogo da Forca em Java

Um projeto simples, didático e divertido que simula o clássico **Jogo da Forca**, desenvolvido inteiramente em **Java puro**. Ideal para praticar fundamentos da linguagem, lógica de programação, controle de fluxo e manipulação de arrays e strings.

## 📌 Sobre o Projeto

O jogo consiste em adivinhar uma palavra secreta (pré-definida como "JAVA") com um número limitado de tentativas. A cada erro, o jogador perde uma tentativa. O jogo termina quando:
- O jogador adivinha corretamente todas as letras da palavra, ou
- O número de tentativas chega a zero.

Este projeto foi desenvolvido com foco em **didática e clareza**, sendo ideal para iniciantes na linguagem Java ou para uso em aulas e tutoriais introdutórios.

## 💡 Funcionalidades

- Mostra o progresso da palavra a ser adivinhada.
- Controla o número de tentativas disponíveis.
- Informa se a letra digitada está ou não na palavra.
- Exibe mensagem de vitória ou derrota ao final do jogo.
- Lida com letras maiúsculas de forma robusta.

## 🧠 Conceitos Aplicados

- Estruturas de controle (`if`, `for`, `while`)
- Manipulação de arrays de caracteres
- Interação com o usuário via `Scanner`
- Comparações de strings em Java
- Uso de `charAt`, `toUpperCase`, `String.valueOf`
- Princípios básicos de design de jogos por terminal

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/DevRafaSantos/jogo-da-forca-java.git
   cd jogo-da-forca-java
   ```

2. Compile e execute o código:
   ```bash
   javac JogoDaForca.java
   java secao15_JogoDaForca.JogoDaForca
   ```

3. Jogue diretamente pelo terminal!

## 📷 Exemplo de Uso

```
Palavra: _ _ _ _
Tentativas restantes: 6
Digite uma letra:
A
Letra correta.
Palavra: _ A _ A

Digite uma letra:
J
Letra correta.
Palavra: J A _ A

...

Parabéns, você venceu! Ainda restavam 3 tentativas.
A palavra era: JAVA
```

## 🎓 Aprendizados e Propósito

Esse projeto faz parte dos meus estudos em **Java** e foi desenvolvido para consolidar conceitos fundamentais da linguagem. É uma forma de mostrar, aos recrutadores e colegas de tecnologia, minha evolução na área de **desenvolvimento backend** e **pensamento lógico**.

## 📁 Estrutura do Projeto

```
├── secao15_JogoDaForca/
│   └── JogoDaForca.java
```

## 🤝 Contribuições

Sugestões e melhorias são sempre bem-vindas. Sinta-se à vontade para abrir issues ou pull requests!

## 📫 Contato

Desenvolvido com 💻 por **Rafael Santos de Andrade**  
