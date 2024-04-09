---
layout: default
title: Exercício testes de desenvolvimento
parent: Teste de desenvolvimento
nav_order: 18
---

## Teste unitário com Junit

### Logistics 

Você foi designado para criar testes unitários para a classe `Vehicle`, que
representa um veículo capaz de transportar cargas até um limite máximo de peso.
A classe `Vehicle` já está implementada, mas agora é necessário garantir que
todas as funcionalidades do veículo estejam corretas por meio de testes
unitários.

Instruções:

Examine a classe `Vehicle` fornecida no projeto logistics. Ela possui três
métodos: `addWeight`, `checkWeightLimit`, e um construtor. Crie uma classe de 
teste chamada `VehicleTest` para testar os métodos da classe `Vehicle`. Utilize
o framework JUnit para escrever seus testes.
Implemente pelo menos três cenários de teste para cada método da classe
`Vehicle`. Considere os seguintes casos:

- Adição de cargas ao veículo.

- Verificação do limite de peso com diferentes cargas.

- Verificação do limite de peso com um veículo vazio.

- Garanta que seus testes cubram todos os possíveis cenários e que os métodos da
classe `Vehicle` estejam funcionando conforme o esperado.

Execute os testes e verifique se todos eles passam com sucesso. Caso algum teste
falhe, depure o código da classe `Vehicle` para corrigir o problema e execute os
testes novamente até que todos passem.

Observações:

Certifique-se de que seus testes abranjam uma variedade de casos de uso para
garantir que o `Vehicle` funcione corretamente em todas as situações. Isso
inclui testar diferentes combinações de cargas e verificar se o limite de peso
é respeitado. Certifique-se de que os nomes dos testes sejam descritivos e
explicativos.