# Contador em JavaFX

Este projeto consiste em um simples contador implementado em JavaFX. O contador permite incrementar e decrementar um valor exibido na interface gráfica.

## Tecnologias Utilizadas
- Java
- JavaFX
- CSS

## Funcionalidades
- Exibição do valor atual do contador
- Botão para incrementar o contador
- Botão para decrementar o contador
- Mudança de cor do número conforme o valor:
  - **Verde** para valores positivos
  - **Vermelho** para valores negativos
  - **Branco** para zero

## Estrutura do Projeto
```
├── src/
│   ├── basico/
│   │   ├── Contador.java
│   │   ├── Contador.css
```

## Como Executar o Projeto
1. Certifique-se de ter o Java e o JavaFX instalados.
2. Compile o código-fonte:
   ```sh
   javac --module-path "<caminho-do-javafx>" --add-modules javafx.controls src/basico/Contador.java
   ```
3. Execute o programa:
   ```sh
   java --module-path "<caminho-do-javafx>" --add-modules javafx.controls basico.Contador
   ```

Substitua `<caminho-do-javafx>` pelo caminho onde o JavaFX está instalado.

## Exemplo de Interface
A interface apresenta um design simples e funcional, com botões arredondados e um fundo escuro, estilizado via CSS.

## Estilização (CSS)
O arquivo `Contador.css` define as cores e o estilo dos elementos da interface.
