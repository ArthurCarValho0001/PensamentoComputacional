# Registro de Erros Identificados

## 1. Erro de Entrada de Dados
### Problema
O sistema aceitava campos vazios ou valores inválidos.

### Impacto
Gerava falhas de execução e resultados incorretos.

### Solução Aplicada
Foi criada validação para impedir dados nulos ou inválidos.

---

## 2. Erro Lógico
### Problema
A condição utilizada no cálculo principal estava invertida.

### Impacto
O sistema retornava resultados errados em determinadas situações.

### Solução Aplicada
A lógica condicional foi reorganizada e testada.

---

## 3. Erro de Execução
### Problema
O programa encerrava ao tentar acessar uma variável inexistente.

### Impacto
Interrupção do funcionamento do sistema.

### Solução Aplicada
Foi implementado tratamento de exceções e verificação prévia da variável.

---

## 4. Erro de Interface
### Problema
Mensagens de erro não eram claras para o usuário.

### Impacto
Dificuldade de utilização do sistema.

### Solução Aplicada
As mensagens foram padronizadas com linguagem simples e objetiva.