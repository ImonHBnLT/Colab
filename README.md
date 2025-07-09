> 📘 This README is available in: [🇺🇸 English](README.en.md) | [🇧🇷 Português](README.md)


## 🔐 RSA Encryption Example
Implementa o algoritmo de criptografia RSA em Python, incluindo geração de chaves, encriptação de mensagens com chaves públicas e decriptação com chaves privadas.
### Destaques:
- Geração de primos aleatórios e verificação de primalidade
- Cálculo das chaves pública (`E`) e privada (`D`) com base no totiente (`Z`)
- Função de inverso modular para obtenção de `E`
- Criptografia de texto com base em valores ASCII
- Sistema de entrada/saída para teste de mensagens e valores personalizados
### Ideal para compreensão dos princípios da criptografia RSA e testes com algoritmos simples.

---

## 🚚 Otimização de Carga Veicular com Gurobi
Resolve um problema de carga de veículo utilizando programação linear inteira, considerando peso máximo, valor dos produtos, quantidades disponíveis e restrições de incompatibilidade entre itens.
### Principais componentes:
- Leitura de dados de arquivo .txt com informações sobre os produtos
- Definição de variáveis inteiras (x[i]) e binárias (y[i]) para controle de inclusão de itens
- Função objetivo: maximizar o valor total da carga
- Restrições:
  - Capacidade máxima de peso do veículo
  - Quantidade limitada por item
  - Incompatibilidades entre pares de produtos
### Retorno da solução ótima com lista dos itens selecionados e peso total carregado

---

## 🏭 Otimização de Distribuição Fábrica-Cliente com Gurobi
Executa um modelo de programação linear contínua para minimizar o custo de envio de produtos entre múltiplas fábricas e clientes, respeitando limites de estoque, demandas e custos logísticos.
### Componentes principais:
- Leitura de matrizes para estoque das fábricas, demanda dos clientes e custo por envio
- Definição de variáveis contínuas para quantidades enviadas
- Função objetivo: minimizar o custo total de transporte
- Restrições:
  - Cada cliente recebe exatamente o que precisa de cada produto
  - Fábricas não excedem o próprio estoque disponível
  - Retorna a quantidade a ser enviada por fábrica, cliente e produto, junto ao custo ótimo de distribuição
### Ideal para simular problemas reais de logística com múltiplas origens e destinos.
