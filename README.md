# 🔢 Sorteador de Números

Bem-vindo ao **Sorteador de Números**! Este projeto foi desenvolvido para sortear números aleatórios dentro de um intervalo definido pelo usuário, evitando repetições. A interface permite definir a quantidade de números e o intervalo desejado de forma dinâmica.

## 🎨 Tecnologias Utilizadas

- **HTML**: Estrutura da página.
- **CSS**: Estilização e layout do sorteador.
- **JavaScript**: Lógica de funcionamento para realizar o sorteio e atualizar a interface.

## 🛠️ Funcionalidades

- **Definir Intervalo**: O usuário pode inserir o intervalo numérico desejado nos campos "Do número" e "Até o número".
- **Quantidade de Números**: O usuário define quantos números serão sorteados.
- **Sorteio sem Repetição**: Garante que todos os números sorteados sejam únicos.
- **Reiniciar Sorteio**: Limpa as entradas e os resultados, permitindo iniciar um novo sorteio.

## 💻 Como Funciona

1. **Entrada do Usuário**: O usuário define a quantidade de números, o intervalo mínimo e máximo.
2. **Sorteio de Números**: A função `sortear()` gera números aleatórios únicos dentro do intervalo especificado. Se um número já foi sorteado, a função sorteia novamente até encontrar um número inédito.
3. **Manipulação de DOM**: A interface é atualizada dinamicamente, exibindo os números sorteados e alterando o estado do botão "Reiniciar" para habilitado.

## 📸 Screenshot

![Sorteador de Números](https://github.com/user-attachments/assets/97738ad7-9069-4db0-a549-604cf8d286a2)


## 📝 Observações

- **Funções Auxiliares**: A função `obterNumeroAleatorio(min, max)` é utilizada para gerar os números aleatórios dentro do intervalo.
- **Botão Dinâmico**: O botão "Reiniciar" é desabilitado por padrão e só é habilitado após o sorteio, garantindo uma interação clara e intuitiva.
- **Responsividade**: O design é responsivo e se adapta a diferentes tamanhos de tela, proporcionando uma experiência consistente em dispositivos móveis e desktops.

## 🚀 Como Executar

Para visualizar e testar o projeto, basta abrir o arquivo `index.html` no seu navegador.

## 🖼️ Design

O design do projeto é moderno e interativo, com cores vibrantes e uma interface limpa, permitindo uma experiência de usuário agradável e intuitiva.

---

Feito com ❤️ por Natália


