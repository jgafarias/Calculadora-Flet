# Calculadora com Flet

Este projeto é uma calculadora interativa desenvolvida com o framework **Flet**, projetada para operar diretamente em um aplicativo de desktop. Com ela, você pode realizar operações básicas de cálculo de forma simples e intuitiva.

## Características

- **Interface amigável:** Design moderno com botões bem organizados.
- **Funções suportadas:**
  - Adição (`+`)
  - Subtração (`-`)
  - Multiplicação (`*`)
  - Divisão (`/`)
  - Cálculo de porcentagem (`%`)
- **Recursos adicionais:**
  - Limpeza de toda a tela (`C`)
  - Remoção de último dígito (`Delete`)
  - Entrada de números decimais (`.`)
  - Resultado instantâneo (`=`)

## Estrutura do Código

- **Interface do Usuário (UI):** Construída usando o Flet, com estilos personalizados para botões, como números, operadores e funções.
- **Funções principais:**
  - `entering_values(e)`: Lida com a entrada de valores e operadores.
  - `clear_screen(e)`: Limpa toda a entrada atual.
  - `calculate(e)`: Realiza o cálculo com base nos valores inseridos.
  - `delete(e)`: Remove o último caractere inserido.

## Dependências

Antes de executar o projeto, você precisará instalar as seguintes dependências:

```bash
pip install flet
```

## Como Usar

Siga os passos abaixo para usar a calculadora:

1. **Inicie o aplicativo:**
   - Execute o script da calculadora no terminal com o comando `python calculadora.py`.

2. **Interface do Usuário:**
   - A interface exibirá uma tela de exibição para os resultados e um conjunto de botões para realizar as operações.

3. **Insira os números e operadores:**
   - Clique nos botões numéricos (`0-9`) para inserir os números.
   - Utilize os operadores (`+`, `-`, `*`, `/`, `%`) para definir as operações desejadas.
   - Para números decimais, use o botão `.`.

4. **Realize cálculos:**
   - Após inserir uma operação, clique no botão `=` para exibir o resultado na tela.

5. **Funções extras:**
   - Clique no botão `C` para limpar toda a entrada atual.
   - Utilize o botão `Delete` para apagar o último dígito inserido.

6. **Personalização:**
   - Você pode personalizar as cores, estilos e dimensões da calculadora editando as variáveis no código, como `page.bgcolor` ou os estilos dos botões.

7. **Encerrando o aplicativo:**
   - Para fechar o aplicativo, basta encerrar a execução do script diretamente no terminal ou clicar no botão de fechar da janela.

Com isso, você poderá realizar cálculos com facilidade e praticidade!

## Requisitos
- Python 3.x
- Flet

## Contato

Para mais informações, entre em contato com o autor:

- **Nome:** João Gabriel
- **GitHub:** [jgafarias](https://github.com/jgafarias)
