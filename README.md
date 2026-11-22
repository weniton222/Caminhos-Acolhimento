# Caminhos & Acolhimento

Site de prevenção primária da violência contra a mulher, desenvolvido como projeto acadêmico de Produto Técnico e Tecnológico (PTT).

O foco é agir antes que a violência comece: mostrar como é uma relação saudável, ajudar a perceber cedo os primeiros sinais de controle e indicar onde buscar orientação.

O site é anônimo, não pede cadastro e funciona em qualquer navegador, no celular ou no computador.

## Um único arquivo, cinco abas

Todo o site está em `index.html` (HTML, estilos e script juntos). O conteúdo é dividido em abas, no topo da página:

| Aba | O que tem |
| --- | --- |
| Início | Mensagem de prevenção e os três passos: aprender, perceber e agir cedo. |
| Relação saudável | Sinais de cuidado e sinais de alerta lado a lado, seis mitos explicados e o que cada pessoa pode fazer para prevenir. |
| Termômetro | 20 perguntas da OMS: 7 sobre sinais de controle e 13 do questionário WHO VAW. Mostra o degrau em que a relação está, se ela vem piorando e um plano de caminhos. |
| Entenda | As cinco formas de violência da Lei Maria da Penha e o ciclo da violência. |
| Rede de ajuda | Emergência, proteção e direitos, apoio psicossocial, trabalho e autonomia (Sine, cursos gratuitos, Cadastro Único) e cuidados para navegar com segurança. |

A seção **Método e fontes** abre pelo rodapé e pelo resultado do termômetro. Os botões 190 e 180 ficam no rodapé de todas as abas.

Dá para abrir direto em uma aba pelo endereço: `index.html#saudavel`, `#auto`, `#entenda`, `#ajuda` ou `#metodo`.

## O questionário

O termômetro tem duas partes e foi pensado para mostrar não só se há violência, mas se a relação está piorando.

### Parte 1: sinais de controle

Sete perguntas sobre comportamentos de controle do Estudo Multipaíses da OMS (García-Moreno et al., 2005), em tradução do grupo. No estudo, o número de comportamentos de controle se associou ao risco de violência física ou sexual.

Enunciado: "Pensando no seu parceiro atual ou no mais recente, em geral ele:"

1. Tenta impedir que você veja suas amigas e amigos?
2. Tenta restringir o seu contato com a sua família?
3. Insiste em saber onde você está o tempo todo?
4. Ignora você ou a trata com indiferença?
5. Fica zangado se você conversa com outro homem?
6. Desconfia com frequência de que você é infiel?
7. Espera que você peça permissão a ele antes de procurar um serviço de saúde?

### Parte 2: WHO VAW

A parte 2 usa o instrumento **WHO VAW**, do Estudo Multipaíses da OMS sobre Saúde da Mulher e Violência Doméstica, na versão brasileira validada por Schraiber et al. (2010). A redação das perguntas é a da versão validada.

Enunciado: "Nos últimos 12 meses, seu parceiro atual ou algum ex-parceiro:". Respostas: sim ou não, com a opção de não responder.

| Nº | Tipo | Pergunta |
| --- | --- | --- |
| 1 | Psicológica | Insultou-a ou fez com que você se sentisse mal a respeito de si mesma? |
| 2 | Psicológica | Depreciou ou humilhou você diante de outras pessoas? |
| 3 | Psicológica | Fez coisas para assustá-la ou intimidá-la de propósito? |
| 4 | Psicológica | Ameaçou machucá-la ou alguém de quem você gosta? |
| 5 | Física, moderada | Deu-lhe um tapa ou jogou algo em você que poderia machucá-la? |
| 6 | Física, moderada | Empurrou-a ou deu-lhe um tranco ou chacoalhão? |
| 7 | Física, grave | Machucou-a com um soco ou com algum objeto? |
| 8 | Física, grave | Deu-lhe um chute, arrastou ou surrou você? |
| 9 | Física, grave | Estrangulou ou queimou você de propósito? |
| 10 | Física, grave | Ameaçou usar ou realmente usou arma de fogo, faca ou outro tipo de arma contra você? |
| 11 | Sexual | Forçou-a fisicamente a manter relações sexuais quando você não queria? |
| 12 | Sexual | Você teve relação sexual porque estava com medo do que ele pudesse fazer? |
| 13 | Sexual | Forçou-a a uma prática sexual degradante ou humilhante? |

## Como a pontuação é feita

| Passo | Regra | Origem |
| --- | --- | --- |
| 1. Sinais de controle | Parte 1. Cada "sim" conta um sinal, de 0 a 7. Não entram no escore de violência. | Perguntas de García-Moreno et al., 2005; contagem do grupo |
| 2. Escore de violência | Parte 2. Cada "sim" vale 1 ponto. Escore de 0 a 13, sem peso por pergunta. | Schraiber et al., 2010 |
| 3. Tipo de violência | Presente quando há pelo menos um "sim" no grupo: psicológica (1 a 4), física (5 a 10), sexual (11 a 13). | García-Moreno et al., 2005 |
| 4. Gravidade da violência física | Moderada quando só as perguntas 5 e 6 têm "sim". Grave quando há "sim" em qualquer pergunta de 7 a 10. | García-Moreno et al., 2005; Schraiber et al., 2007 |
| 5. Degrau do termômetro | Atenção: só sinais de controle. Amarelo: violência psicológica. Laranja: física moderada. Vermelho: física grave ou sexual. Vale sempre o degrau mais alto. | Regra de leitura do site |

Exemplos: só um sinal de controle dá escore 0 e degrau de atenção. Só a pergunta 1 da parte 2 com "sim" dá escore 1 e amarelo. Só a pergunta 5 dá escore 1 e laranja. Só a pergunta 10 (arma) dá escore 1 e vermelho.

### Limites

- Os passos 2 a 4 vêm da literatura. O passo 5 (os quatro degraus) é uma regra de leitura do site.
- As perguntas de controle são tradução do grupo e não têm ponto de corte: um sinal isolado pede atenção, não é diagnóstico.
- Todo resultado traz o bloco "A relação mudou?", que orienta a comparar com o começo da relação e a refazer o teste depois de alguns meses. Como nada é salvo, essa comparação depende da memória da usuária.
- O instrumento foi validado em entrevistas presenciais, com entrevistadoras treinadas. Aqui é autopreenchido, pela internet e só para os últimos 12 meses, o que pode mudar seu desempenho.
- O escore não tem ponto de corte para diagnóstico. O resultado é uma triagem educativa.
- O questionário não mede violência moral nem patrimonial.

## Outros referenciais

| Referencial | Para que serve no site |
| --- | --- |
| RESPECT (OMS e ONU Mulheres, 2019) | Organiza o conteúdo de prevenção primária. O site trabalha quatro das sete estratégias: relações, empoderamento, serviços e atitudes e normas. |
| FRIDA (CNMP, 2019) | Avaliação de risco aplicada por profissional capacitado. O site não o substitui; quando o resultado é vermelho, orienta a procurar essa avaliação. |

## Cuidados contra viés de informação

- Perguntas com a redação validada, que descrevem atos concretos, sem a palavra "violência".
- Período definido na parte 2: últimos 12 meses.
- Mesma resposta em todas as perguntas (sim ou não), com opção de não responder; o resultado avisa quando faltam respostas.
- Escore, tipos e degraus só aparecem no resultado.
- Anonimato: sem cadastro e sem armazenamento.
- Fontes indicadas em cada conteúdo; o que é redação do grupo está identificado.

## Saída rápida e privacidade

- O botão **Saída rápida**, fixo no topo, esconde o conteúdo, apaga as respostas e troca a página por um site de busca, sem deixar o endereço no botão "voltar".
- Nenhuma resposta é salva ou enviada: tudo fica na memória da página e some ao sair.
- Não há cadastro, cookies nem ferramentas de rastreamento.
- O histórico do navegador ainda registra a visita. Por isso o site orienta a usar aba anônima.

## Como abrir e publicar

Baixe `index.html` e abra no navegador. Para publicar com o GitHub Pages:

1. No repositório, abra **Settings › Pages**.
2. Em **Source**, escolha **Deploy from a branch**.
3. Selecione a branch `main`, pasta `/ (root)`, e salve.
4. Em alguns minutos o site fica disponível em `https://weniton222.github.io/Caminhos-Acolhimento/`.

## Pendências antes de divulgar

- Confirmar por telefone os contatos da rede de Uberlândia (DEAM, Defensoria Pública, Casa da Mulher, Sine e Centros Profissionalizantes).
- Preencher os campos entre colchetes: horário da DEAM, endereços de CRAS/CREAS, grupos de apoio, dados do grupo no rodapé e a referência dos sinais, mitos e dicas.

## Referências

- SCHRAIBER, L. B.; LATORRE, M. R. D. O.; FRANÇA JR., I.; SEGRI, N. J.; D'OLIVEIRA, A. F. P. L. Validade do instrumento WHO VAW STUDY para estimar violência de gênero contra a mulher. Revista de Saúde Pública, v. 44, n. 4, p. 658-666, 2010. DOI: 10.1590/S0034-89102010000400009.
- SCHRAIBER, L. B. et al. Prevalência da violência contra a mulher por parceiro íntimo em regiões do Brasil. Revista de Saúde Pública, v. 41, n. 5, p. 797-807, 2007.
- GARCÍA-MORENO, C.; JANSEN, H. A. F. M.; ELLSBERG, M.; HEISE, L.; WATTS, C. WHO Multi-country Study on Women's Health and Domestic Violence against Women: initial results on prevalence, health outcomes and women's responses. Geneva: World Health Organization, 2005.
- CONSELHO NACIONAL DO MINISTÉRIO PÚBLICO. Formulário de Avaliação de Risco FRIDA. Brasília: CNMP, 2019.
- WORLD HEALTH ORGANIZATION; UN WOMEN. RESPECT Women: preventing violence against women. Geneva: WHO, 2019.
- BRASIL. Lei nº 11.340, de 7 de agosto de 2006 (Lei Maria da Penha).
- Ciclo da violência, descrito por Lenore Walker (1979), conforme a Procuradoria da Mulher da Câmara Municipal de São Paulo.
- Central de Atendimento à Mulher, Ligue 180 (gov.br).
- Prefeitura de Uberlândia, Proteção à Mulher e Formação Profissional.
- BRASIL. Lei nº 14.542, de 3 de abril de 2023 (prioridade no Sine para mulheres em situação de violência doméstica).

Este site informa e orienta. Ele não substitui o atendimento de profissionais. Em caso de perigo, ligue 190.
