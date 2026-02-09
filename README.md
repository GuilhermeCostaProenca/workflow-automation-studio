# AutoTarefas

    [![CI](https://github.com/GuilhermeCostaProenca/autotarefas/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/GuilhermeCostaProenca/autotarefas/actions/workflows/ci.yml)

    Projeto de produto digital para resolver dor real de mercado com execu??o em padr?o profissional de portf?lio.

    ## Proposta
    **Automa??o acess?vel de tarefas repetitivas** para PMEs e ?reas operacionais com tarefas manuais recorrentes.

    ## Problema
    Processos repetitivos e suscet?veis a erro ainda feitos manualmente por falta de RPA simples e barato.

    ## P?blico-alvo
    PMEs e ?reas operacionais com tarefas manuais recorrentes

    ## Stack sugerida
    Frontend React, API Fastify, motor de automa??o Playwright, PostgreSQL, fila Redis

    ## MVP inicial
    - Gravador de fluxo (no-code) para tarefas em navegador e planilhas
    - Agendamento e execu??o em segundo plano com logs
    - Tratamento de falhas e repeti??o autom?tica
    - Cat?logo de templates para finan?as, RH e opera??es

    ## Estrutura base
    - `README.md`: vis?o do produto e execu??o.
    - `PRD.md`: escopo funcional e regras de produto.
    - `ARCHITECTURE.md`: desenho t?cnico inicial.
    - `BACKLOG.md`: backlog priorizado por valor.
    - `PLAN.md`: plano de execu??o em fases.
    - `.github/workflows/ci.yml`: pipeline de valida??o.

    ## Como come?ar
    1. Refinar PRD com recorte de usu?rio e problema.
    2. Definir arquitetura de refer?ncia e stack final.
    3. Implementar fluxo principal ponta a ponta.
    4. Subir CI, testes essenciais e documenta??o de uso.

    ## Riscos principais
    Mudan?as de interface em sistemas terceiros e robustez de automa??es

    ## Contexto da ideia
    AutoTarefas –  automação  acessível  de  tarefas  repetitivas:  Em  muitas  pequenas  empresas,
funcionários perdem horas em tarefas manuais e chatas – copiar dados de uma planilha para
outra, gerar relatórios, cadastrar informações em dois sistemas diferentes que não “conversam”
etc.  Essa  é  uma  dor  real  de  produtividade:  trabalhos  repetitivos  e  propensos  a  erro,  que
grandes corporações já automatizam com RPA (Robotic Process Automation). O problema é que
as  ferramentas  de  RPA  atuais  são  complexas  e  caras,  exigindo  infraestrutura  e  pessoal
especializado – muitas empresas menores nem tentam, pois “é complicado e custoso montar
estrutura de RPA, contratar ou treinar pessoal para isso”.  Por que não está resolvido?
Soluções de automação existem, mas foram feitas para gigantes, com preço e dificuldade à
altura.  Falta  uma  maneira  simples  (até  no-code)  de  um  pequeno  negócio  automatizar  suas
“planilhas e cliques” sem investir uma fortuna.  Quem sente a dor: times financeiros fazendo
lançamento manual, RH inserindo dados em múltiplos sistemas, operações copiando pedido de
um  sistema  para  outro  –  principalmente  PMEs  e  profissionais  administrativos
sobrecarregados.  Projeto provisório:AutoTarefas, um “RPA de bolso” onde qualquer um grava
passos repetitivos no computador e o robô faz por você depois, liberando tempo e evitando
erros.
