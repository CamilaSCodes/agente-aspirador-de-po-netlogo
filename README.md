# Agente Inteligente - Cenário adaptado do "Mundo do Aspirador de Pó" no Netlogo
## 1º Avaliação Experimental de Inteligência Computacional 

Este repositório contém a implementação de agentes inteligentes em ambientes simulados, com o objetivo de compreender os conceitos fundamentais relacionados à inteligência artificial, projetar agentes reativos e baseados em modelos, e avaliar seu desempenho em tarefas simuladas.

## Metodologia 

1. Leitura dos Materiais:

    * Capítulo 2: *Agentes Inteligentes* do livro "Inteligência Artificial" de Stuart Russell e Peter Norvig.
    * Capítulo 2: *Intelligent Agents* do livro "An Introduction to Multiagent Systems" de Michael Wooldridge.

2.  Definições e Questões:

      Elaborar uma redação sobre Agentes Inteligentes, considerando as seguintes questões. 
    
      a. Qual a definição de agentes?
  
      b. Exemplos de agentes não artificiais?
  
      c. Exemplos de agentes artificiais?
    
      d. Qual a definição de agentes inteligentes ou racionais?
    
      e. Exemplos de agentes artificiais racionais? Medidas de avaliação de desempenho?

      f. Como especificar o ambiente de tarefas (PEAS) e quais as principais propriedades associadas a estes ambientes? O que dizem estas propriedades (em resumo)? Escolha dois agentes inteligentes que você conhece e especifique o PEAS e as propriedades dos ambientes de tarefa.
    
      g. Qual a diferença entre função, programa e arquitetura do agente artificial?
    
      h. Quais são os tipos básicos e as principais diferenças entre as estruturas de programas de agentes propostos?
    
      i. Qual a diferença entre o agente com aprendizagem e os outros quatro tipos básicos de programas de agentes artificiais?

      j. Exemplos de arquiteturas concretas de agentes inteligentes?

3.  Simulação

    Considerando a linguagem disponível na plataforma **NetLogo** implementar um simulador de ambiente de medição de desempenho para uma versão do mundo do
aspirador de pó. A implementação deve ser modular, de forma que as características do ambiente (tamanho, forma, localização de sujeira) possam ser alteradas com facilidade.

4. Experimentação

    Fixe o tamanho do ambiente e execute o simulador de ambiente para várias configurações iniciais possíveis de sujeira, obstáculos e posições dos agentes. Registre a pontuação de desempenho dos agentes para cada configuração do ambiente e sua pontuação média global.

5. Relatório

    Entregar um relatório técnico apresentando os mecanismos de atualização de estado interno e de tomada de decisão de cada agente, uma breve descrição do comportamento de cada agente, tabelas, gráficos e uma análise dos resultados a partir do ponto de vista da racionalidade de cada programa.

## Estrutura do Repositório

### Agentes Inteligentes - NetLogo.nlogo

O código simula um agente aspirador de pó que navega por um ambiente de patches, limpando sujeira e evitando obstáculos. Implementa um programa reativo simples e outro baseado em modelos para um agente artificial realizar uma tarefa em um ambiente determinístico e parcialmente observável.

### Agentes Inteligentes - Redação.pdf

Documento contendo uma redação sobre Agentes Inteligentes, considerando as questões elaboradas no Item 2 da seção Metodologia.

### Agentes Inteligentes - Relatório.pdf

Relatório técnico detalhado com a análise do desempenho dos agentes, tabelas de resultados, gráficos e a avaliação da racionalidade de cada agente.

## Instalação e Execução

1. Baixe e instale o [NetLogo](https://ccl.northwestern.edu/netlogo/download.shtml) para simular o ambiente.
2. Faça o download do arquivo `Agentes Inteligentes - NetLogo.nlogo` e abra-o no NetLogo.
3. Execute ambos os agentes para observar a performance em diferentes condições de ambiente.
4. Consulte o relatório técnico para análise detalhada dos resultados.

## Conclusão

O projeto de Avaliação Experimental de Agentes Inteligentes proporcionou uma compreensão mais profunda dos conceitos fundamentais relacionados à inteligência artificial e à aplicação de agentes artificiais em ambientes simulados. Através da implementação de agentes reativos simples e baseados em modelos, foi possível observar como diferentes estratégias de tomada de decisão influenciam o desempenho em ambientes determinísticos e parcialmente observáveis.
