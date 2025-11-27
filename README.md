# Compounding engineering

É uma filosofia de desenvolvimento em que cada ciclo de trabalho melhora o sistema como um todo, tornando futuras tarefas:
- mais rápidas
- mais fáceis
- mais consistentes
- com menos retrabalho

Cada etapa acumula aprendizados e aprimora as bases do projeto.


---
PLAN ⟶ DELEGATE ⟶ ASSESS ⟶ CODIFY ⟶ ⟲ (volta ao PLAN)
---


---
## Plan
Transforma ideias em especificações claras, organizadas e acionáveis. É onde se define o que será feito, por que será feito e como deve ser feito.


- Business Canvas
  - Mapeia o valor do produto ou sistema no nível estratégico.
  
    - Proposta de Valor
      - Define o problema do usuário, os benefícios entregues e o diferencial da solução.
     
        
    - Modelo de Negócio
      - Explica como a solução gera valor e sustenta suas operações (segmentos de clientes, canais, custos, receitas).
     
        
    - Descrição do Produto
      - Especifica funcionalidades principais, público-alvo, necessidades atendidas, fluxo macro de uso.


- UX/UI
  - Define como o usuário interage com o sistema e qual experiência deve ser entregue. Inclui:
    - protótipos
    - fluxos de tela
    - navegação
    - padrões de interface
    - definição de usabilidade


- Feature
  - Descrição estruturada de cada funcionalidade. Contém:
    - objetivo da feature
    - regras de negócio
    - cenários de uso
    - escopos
    - critérios de aceitação
   
  
- Requirements
  - Requisitos funcionais e não funcionais:
    - performance
    - segurança
    - acessibilidade
    - compatibilidade
    - restrições técnicas


- Coding Guidelines
  - Definem o estilo de código adotado no projeto:
    - regras de nomeação
    - padrões de formatação
    - estrutura de arquivos
    - convenções internas
    - como documentar funções e módulos


- Architecture
  - Define a estrutura técnica do sistema:
  -   camadas
  -   padrões de design
  -   módulos
  -   integrações
  -   decisões técnicas justificadas

---
## Delegate
Etapa responsável por atribuir tarefas a agentes, desenvolvedores ou pipelines automáticos.


- Coding Agent development
  - Um agente (IA ou script) é configurado para:
    - gerar código conforme guidelines
    - seguir a arquitetura definida
    - usar padrões de qualidade
    - criar arquivos, funções, módulos e testes automaticamente

   
- Open PR
  - Cada entrega passa pela abertura de um Pull Request, onde o código será avaliado, comentado, revisado e testado antes de entrar na branch principal. Garante rastreabilidade e evita inserção de código sem controle.
 

---
## Asses
verifica qualidade, segurança, estilo, estrutura e riscos antes de aprovar um commit, um pull request ou uma nova feature

- Automated Code Review
  - lint (verifica uso incorreto de variáveis, formatação inconsistente, identação errada, código morto, padrões que podem gerar bugs, violações de estilo)
 

  - sonar (verifica qualidade do código, vulnerabilidades de segurança, bugs potenciais, duplicação de código, complexidade ciclomática, dívida técnica, cobertura de testes)
 
    
  -  agentic code (consegue encontrar erros de arquitetura, comparar com padrões de design, sugerir refatoração, verificar coerência com o restante do projeto, validar se aquela solução segue as práticas da equipe, checar documentação, analisar impacto global, detectar inconsistências lógicas)
 


## Codify

- New guidelines inside
- CLAUDE.md
- AGENT.md
