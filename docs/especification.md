# Especificações do Projeto

## Personas

1) Mariana tem 14 anos e está cursando o primeiro ano do ensino médio em uma escola municipal no bairro de Campo Grande. Ela gosta de computadores e da saga Star Wars, mas sua mãe acha que isso é "coisa de menino". Ela acha que não é "boa com números", mas se sente frustrada por não conseguir decidir qual faculdade cursar. Ela viu na internet um curso de Robótica e gostou muito da ideia, mas era muito caro e sua mãe não tinha como pagar. Na sua escola, as feiras de Ciências são raras, pois a escola não possui infraestrutura para manter os laboratórios funcionando, então dificilmente ela tem aulas práticas. Os professores acham Mariana muito inteligente e curiosa e que ela deveria fazer uma faculdade. Ela, por sua vez, está um pouco desanimada, pois várias amigas suas estão abandonando a escola para se casar e/ou cuidar de filhos e ela acha que vai acabar como suas amigas. Ela usa a internet através do seu celular, pois não tem computador em casa, mas usa o da vizinha quando pode para pesquisar cursos e atividades gratuitas que possam lhe interessar.

2) Jorge tem 54 anos e é professor de Física em uma escola estadual em Cascadura, dando aulas para adolescente do ensino médio. Ele gosta muito de dar aulas, mas ele não sabe o que fazer para os alunos prestarem mais atenção. As notas dos alunos são baixas e o laboratório está desativado há anos por falta de insumos e equipamentos. Apesar dele amar o que faz, está se sentindo muito frustrado por não conseguir fazer seus alunos aprender. Ele gosta de participar de eventos de capacitação e em um deles viu uma professora utilizando materiais do dia a dia para explicar assuntos de Biologia e ficou maravilhado. Porém, não sabe com adaptar isso para as aulas de Física, pois não se sente muito criativo para tal.

3) Elizabeth tem 45 anos e é diretora de uma escola municipal em Caxias. Ela é muito proativa e gostaria de mudar a realidade dos alunos de sua escola. Professora de Matemática de formação, ela própria tem uma história de desafios que conta com muito orgulho. Mulher, negra e pobre, conseguiu fazer faculdade pública com muito sacrifício e agora, como diretora, sonha em melhorar a infraestrutura de sua escola. Atualmente, já possui várias iniciativas de atividades de visita a museus, instituições e universidades para que seus alunos possam conhecer o máximo de opções que elas podem ter ao se formar. Porém, ela ainda encontra um pouco de resistência das meninas em participar de atividades que envolvam Ciências Exatas. O laboratório de Informática é modesto, mas ela sonha em oferecer alguma atividade com o pouco que tem, porém não há professores capacitados para tal no momento.

4) Gisele tem 37 anos e é formada em Ciência da Computação. Ela presta serviços na área de Internet das Coisas em uma empresa privada e dá aula em uma Universidade Pública para vários cursos da Área de Exatas. Seu sonho sempre foi fazer trabalhos voluntários na área de educação e, por isso, já participou de diversos projetos, inclusive durante sua faculdade. Ela lembra que, da turma dela, só tinha ela e mais duas meninas, e todo resto da turma era de homens. Era o que gostava de fazer, mas isso sempre a incomodou, e lembra como foi difícil enfrentar os preconceitos da família, dos colegas e dos professores homens. Ela gostaria de ajudar meninas que, como ela, gostam de computadores, mas tem receio por achar que esses cursos "são pra homens". Ela não sabe por onde começar, nem como poderia ajudar, mas está aberta para iniciativas que levem coragem pra essas meninas.

5) Pedro tem 49 anos e possui uma loja de embalagens em sociedade com sua esposa, Fernanda, em Jacarepaguá. O casal tem uma filha, Helena, de 12 anos, estudante em uma escola particular que oferece aulas de Robótica e Informática para seus alunos. Ele ficou impressionado quando a filha levou para casa um dos projetos para mostrar a seus pais. Pedro nunca estudou em escolas privadas e lembrou que na sua escola nunca teve infraestrutura pra isso. Fernanda, que estava fazendo uma pós-graduação, disse a ele que em sua faculdade havia projetos de extensão que faziam atividades desse tipo em algumas escolas públicas e ele ficou encantado e queria muito ajudar, mas não sabia como. Ele já reservava parte de seus lucros para atividades em sua própria comunidade, o que o tornava benquisto na região por estar sempre colaborando em projetos sociais.

## Histórias de Usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`    | QUERO/PRECISO ... `FUNCIONALIDADE`     |PARA ... `MOTIVO/VALOR`                                                                                         |
|------------------------|----------------------------------------|----------------------------------------------------------------------------------------------------------------|
|Aluna                   | Encontrar informação                   | Conhecer o projeto                                                                                             |
|Aluna                   | Cadastrar Perfil                       | Acessar as aulas e materiais didáticos voltado para alunos                                                     |
|Professor Usuário       | Encontrar informação                   | Conhecer o projeto                                                                                             |
|Professor Usuário       | Cadastrar Perfil                       | Acessar as aulas e materiais didáticos voltado para professores                                                |
|Professor Colaborador   | Encontrar informação                   | Conhecer o projeto                                                                                             |
|Professor Colaborador   | Cadastrar Perfil                       | Acessar as aulas e materiais didáticos voltado para professores e o calendário de treinamento de colaboradores |
|Professor Colaborador   | Inscrever-se em Treinamento            | Inscrever-se em turma disponível para treinamento de colaboradores                                             |
|Professor Colaborador   | Colaborar                              | Inscrever-se em evento disponível para cadastro de colaboradores                                               |
|Professor Colaborador   | Gerar Agenda de Aulas                  | Gerar agenda de aulas marcadas (eventos)                                                                       |
|Pessoa Jurídica Privada | Encontrar informação                   | Conhecer o projeto                                                                                             |
|Pessoa Jurídica Privada | Cadastrar Perfil                       | Inscreve-se como investidor                                                                                    |
|Pessoa Jurídica Privada | Investir                               | Inscrever-se para investir em aula prática em escola pública                                                   |
|Pessoa Jurídica Privada | Gerar Recibo de Doação                 | Gerar recibo de doação para o IR                                                                               |
|Escola Pública          | Encontrar informação                   | Conhecer o projeto                                                                                             |
|Escola Pública          | Cadastrar Perfil                       | Inscreve-se como escola interessada                                                                            |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito                                                                                                    | Prioridade |
|------|---------------------------------------------------------------------------------------------------------------------------|------------|
|RF-001| Disponibilizar as informações básicas sobre o projeto                                                                     |    ALTA    |
|RF-002| Disponibilizar cadastro de perfil (aluna/professor usuário/professor colaborador/pessoa jurídica privada/escola pública)  |    ALTA    |
|RF-003| Disponibilizar área de perfil (aluna/professor usuário/professor colaborador/pessoa jurídica privada/escola pública)      |    ALTA    |
|RF-004| Disponibilizar aulas e materiais para alunos                                                                              |    ALTA    |
|RF-005| Disponibilizar aulas e materiais para professores                                                                         |    ALTA    |
|RF-006| Disponibilizar agenda de treinamento de professores colaboradores                                                         |    ALTA    |
|RF-007| Disponibilizar pesquisa de escolas públicas locais para investir (mapa)                                                   |    ALTA    |
|RF-008| Disponibilizar agenda de aulas marcadas para professor colaborador                                                        |    ALTA    |
|RF-009| Disponibilizar cadastro de interesse de aula para professores colaboradores treinados                                     |    ALTA    |
|RF-010| Disponibilizar cadastro de investimento na escola escolhida para o investidor                                             |    ALTA    |
|RF-011| Disponibilizar recibo de doação para investidor                                                                           |    ALTA    |
|RF-012| Disponibilizar cadastro de investimento na escola escolhida para o investidor                                             |    ALTA    |
|RF-013| Disponibilizar blog com últimas notícias sobre o projeto                                                                  |    MÉDIA   |
|RF-014| Disponibilizar agenda de palestras e eventos especiais                                                                    |    MÉDIA   |

### Requisitos não Funcionais

|ID     | Descrição do Requisito                                                       | Prioridade |
|-------|------------------------------------------------------------------------------|------------|
|RNF-001| Deverá ser responsivo para rodar em um dispositivos móveis                   |    ALTA    |
|RNF-002| Deverá ser disponibilizado em, pelo menos, 90% do tempo                      |    BAIXA   | 
|RNF-003| Deverá ter tempo de resposta não superior a 3s para solicitação de usuário   |    BAIXA   | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                                                   |
|--|-----------------------------------------------------------------------------|
|01| Deverá ser entregue até o final do semestre (21/12/2023)                    |
|02| Deverá ser desenvolvido em HTML, CSS e Javascript                           |
