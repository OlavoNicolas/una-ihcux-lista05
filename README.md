# una-ihcux-lista05

### Visão Geral
Aplicação em C# para conversão de moedas no console, com foco na aplicação de heurísticas de IHC/UX para melhorar a experiência do usuário.

---

## Heurísticas Aplicadas

### 1. Visibilidade do Status do Sistema

O sistema informa ao usuário o andamento das operações.

**Implementação:**

* Mensagens como:

  * `[SISTEMA]: Conectando ao Banco Central...`
  * `[SISTEMA]: Calculando taxas...`
* Uso de `Thread.Sleep()` para simular processamento

**Benefício:**

* Reduz incerteza e sensação de travamento

---

### 2. Prevenção de Erros

Tratamento de entradas inválidas para evitar falhas.

**Implementação:**

* Bloco `try/catch`
* Conversão com `double.Parse`

**Benefício:**

* Evita interrupções inesperadas
* Retorna mensagem clara ao usuário

---

### 3. Estética e Design Minimalista

Interface limpa e organizada no console.

**Implementação:**

* Uso de cores:

  * Amarelo (título)
  * Verde (resultado)
  * Vermelho (erro)
* Separadores visuais

**Benefício:**

* Melhora legibilidade e foco

---

### 4. Clareza na Entrada de Dados

Orientação direta ao usuário.

**Implementação:**

* Mensagens objetivas:

  * `Digite o valor em REAIS (R$):`
  * `Digite a cotação do DÓLAR hoje:`

**Benefício:**

* Reduz erros de entrada

---

### 5. Feedback Imediato

Resposta rápida após ações do usuário.

**Implementação:**

* Exibição direta do resultado
* Mensagem final de encerramento

**Benefício:**

* Mantém fluidez e controle da interação

---

## Fluxo da Aplicação

1. Exibe cabeçalho
2. Solicita dados
3. Simula processamento
4. Calcula conversão
5. Mostra resultado
6. Trata erros
7. Finaliza execução

---

## Melhorias Futuras

* Uso de `double.TryParse`
* Suporte a múltiplas moedas
* Integração com API de câmbio

---

## Conclusão

O projeto demonstra a aplicação de heurísticas de usabilidade em um ambiente de console, priorizando clareza, feedback e prevenção de erros.




<img width="1919" height="1015" alt="Captura de tela 2026-03-27 160844" src="https://github.com/user-attachments/assets/674d04fb-7ace-4e19-b996-e2e802a62543" />
