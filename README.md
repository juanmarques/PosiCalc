# Calculadora de Preço Médio para Futuros

Este é um projeto simples de uma página da web que fornece uma ferramenta para calcular a margem necessária para ajustar o preço médio de uma posição aberta em contratos futuros de criptomoedas. A calculadora foi projetada para ajudar traders a simular o custo de adicionar a uma posição perdedora (ou vencedora) para atingir um novo preço médio desejado.

A interface é limpa, direta e construída com foco na usabilidade, permitindo que os usuários insiram rapidamente os parâmetros de sua posição e vejam o impacto financeiro de suas decisões estratégicas.

---

## 🚀 Como Usar

Para usar a calculadora, basta abrir o arquivo `index.html` (ou o nome que você deu ao arquivo) em qualquer navegador web. Você verá um formulário com os seguintes campos:

1.  **Tipo de Posição:** Selecione se sua posição atual é **Short (Vendido)** ou **Long (Comprado)**.
2.  **Quantidade Atual da Posição:** Insira o tamanho da sua posição atual (ex: 0.5 BTC, 10 ETH).
3.  **Preço Médio de Entrada Atual:** O preço médio pelo qual sua posição atual foi aberta.
4.  **Preço Atual de Mercado:** O preço atual do ativo, que será usado como base para a nova ordem.
5.  **Novo Preço Médio Desejado:** O seu preço médio alvo após adicionar à posição.
6.  **Sua Alavancagem:** A alavancagem que você está usando na sua conta de futuros (ex: 5, 10, 20).

Após preencher todos os campos, clique no botão **"Calcular"**. O resultado será exibido abaixo, mostrando:
* A quantidade adicional de contratos/moedas que você precisa negociar.
* O valor nocional total dessa nova posição.
* A **margem necessária** (capital que você precisa adicionar) para abrir essa nova posição com a alavancagem especificada.

---

## ⚠️ Aviso de Risco Extremo

Esta ferramenta é para fins educacionais e de simulação. A estratégia de **fazer preço médio**, especialmente ao adicionar a uma posição perdedora, é **extremamente arriscada**.

* **Aumento da Exposição:** Ao adicionar a uma posição perdedora, você aumenta significativamente o seu risco total. Se o mercado continuar a se mover contra você, suas perdas serão amplificadas.
* **Risco de Liquidação:** Aumentar sua posição pode aproximá-lo perigosamente do seu preço de liquidação, resultando na perda total do seu capital na conta de futuros.

**Use esta calculadora como uma ferramenta para entender os custos e riscos, não como uma recomendação de negociação.** Sempre negocie com um plano de gerenciamento de risco claro e nunca arrisque mais do que você pode perder.

---

## 🛠️ Tecnologias Utilizadas

* **HTML:** Estrutura básica da página.
* **Tailwind CSS:** Para estilização rápida e responsiva.
* **JavaScript (Vanilla):** Para toda a lógica de cálculo e manipulação do DOM.
