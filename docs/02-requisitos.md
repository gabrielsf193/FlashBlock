# FlashBlock v0.1

## 1. Requisitos de Projeto

### 1.1 Objetivo

A versão 0.1 do FlashBlock tem como objetivo implementar uma versão inicial e funcional do sistema de flashcards, permitindo ao usuário criar, visualizar e revisar cartões de forma simples.

O foco desta versão é validar o fluxo básico de estudo antes da implementação de funcionalidades mais avançadas, como persistência em banco de dados, autenticação, sincronização e repetição espaçada.

---

## 2. Requisitos Funcionais

### RF01 — Visualização da frente do cartão

O sistema deve permitir que o usuário visualize a informação apresentada na frente de um cartão.

### RF02 — Revelação da resposta

O sistema deve permitir que o usuário revele a resposta localizada no verso do cartão.

### RF03 — Navegação entre cartões

O sistema deve permitir que o usuário avance ou volte a sequência de cartões da lista.

### RF04 — Reinício da revisão

Ao chegar ao último cartão da lista, o sistema deve permitir que o usuário reinicie a sequência de revisão.

### RF05 — Criação de cartões

O sistema deve permitir que o usuário crie novos cartões informando, no mínimo:

* conteúdo da frente;
* conteúdo do verso.

O novo cartão deve ser adicionado à lista disponível para revisão.

### RF06 — Adição de dicas

O sistema deve permitir que o usuário associe uma dica a um cartão.

A dica deve poder ser consultada durante a revisão sem revelar diretamente a resposta.

### RF07 — Visualização da dica

Durante a revisão, o usuário deve conseguir solicitar a exibição da dica associada ao cartão, quando houver uma.

### RF08 — Indicação do progresso

O sistema deve informar ao usuário sua posição atual na sequência de revisão.

Exemplo:

> Cartão 3 de 10

---

# 3. Requisitos Não Funcionais

### RNF01 — Usabilidade

A interface deve apresentar uma estrutura simples e permitir que o usuário compreenda as principais ações sem necessidade de instruções externas.

### RNF02 — Responsividade

A interface deve se adaptar a diferentes tamanhos de tela, permitindo sua utilização tanto em computadores quanto em dispositivos móveis.

### RNF03 — Desempenho

As operações de navegação, revelação de respostas e exibição de dicas devem ocorrer sem atrasos perceptíveis para o usuário.

### RNF04 — Consistência visual

Os elementos da interface devem manter padrões consistentes de tipografia, espaçamento, cores, botões e componentes.

### RNF05 — Acessibilidade básica

Os elementos interativos devem possuir identificação clara de sua função e apresentar contraste suficiente para permitir sua utilização.

### RNF06 — Compatibilidade

A aplicação deve funcionar corretamente nos principais navegadores modernos para desktop e dispositivos móveis.

### RNF07 — Manutenibilidade

O código deve ser organizado de forma modular, permitindo a evolução do sistema e a inclusão de novas funcionalidades sem necessidade de reestruturar completamente a aplicação.

---

# 4. Diretrizes de Interface

As seguintes características visuais fazem parte da definição inicial da interface da versão 0.1:

### UI01 — Estilo visual

A interface deve possuir aparência:

* limpa;
* simples;
* minimalista;
* objetiva.

### UI02 — Cartão

O cartão deve possuir distinção visual entre frente e verso.

O verso utilizará a cor principal predominante definida para a interface.

### UI03 — Controles

Os controles relacionados ao comportamento do cartão devem possuir posicionamento consistente e facilmente identificável.

### UI04 — Dicas de interação

Elementos interativos que necessitem de explicação adicional devem apresentar uma dica de sua função quando o usuário passar o cursor sobre eles em dispositivos que suportem essa interação.

Em dispositivos móveis, a interação não deve depender exclusivamente do uso do mouse.

---

# 5. Escopo da versão 0.1

A versão 0.1 contempla:

* visualização de cartões;
* revelação de respostas;
* navegação entre cartões;
* reinício da sequência;
* criação de cartões;
* adição de dicas;
* visualização de dicas;
* indicação de progresso;
* interface responsiva.

A versão 0.1 **não contempla**:

* criação de contas;
* autenticação;
* banco de dados remoto;
* sincronização entre dispositivos;
* integração com Google Drive;
* algoritmo de repetição espaçada;
* estatísticas avançadas;
* notificações;
* inteligência artificial.

Essas funcionalidades poderão ser consideradas em versões futuras.

---

# 6. Critério de conclusão da v0.1

A versão 0.1 será considerada concluída quando o usuário conseguir realizar o seguinte fluxo:

**Criar um cartão → visualizar a frente → solicitar uma dica → revelar a resposta → avançar para o próximo cartão → percorrer todos os cartões → reiniciar a sequência.**

Além disso, o sistema deverá ser utilizável em computador e dispositivo móvel.



