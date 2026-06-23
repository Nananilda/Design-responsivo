- Quais melhorias foram realizadas
    Foi criada uma identidade visual fixa, além de páginas de conteúdos que facilitam a visualização de todo o material e que sugerem novas matérias e reportagens. Foi desenvolvido também um formulário para contato com validação via JavaScript, além da implementação completa de tags semânticas. O projeto teve sua estrutura, páginas e conteúdos otimizados, contando agora com a criação de setores bem definidos para cada categoria de notícia.

- Quais elementos semânticos foram utilizados
    . <nav>: Define a área de blocos com os links de navegação principal do site.<main>: Determina o conteúdo central, principal e exclusivo de cada página.
    . <article>: Representa uma composição autônoma em uma página, projetada para ser distribuída ou reutilizada de forma independente (como uma notícia).
    . <section>: Agrupa conteúdos semanticamente relacionados e que compartilham uma mesma temática.<footer>: Define o rodapé do documento (geralmente armazena direitos autorais e contatos).
    . <ul>: Define uma lista não ordenada (com marcadores de tópicos).
    . <li>: Representa um item individual pertencente a uma lista.
    . <strong>: Atribui forte importância, seriedade ou urgência a um trecho de texto (além de deixá-lo em negrito).
    . <h2>: Define títulos de segundo nível. É o subtítulo principal da hierarquia do documento.<h3>: Define títulos de terceiro nível, organizando sub-tópicos do conteúdo.
    . <form>: Delimita uma seção interativa para coletar e enviar dados digitados pelo usuário.
    . <input>: Cria campos de digitação de linha única baseados em tipos específicos (texto, e-mail, etc.).
    . <textarea>: Cria um campo de texto expansível com suporte a múltiplas linhas para mensagens.
    . <button>: Cria um botão acionável para submeter dados ou disparar eventos em scripts.
    . Atributo alt (Acessibilidade): (Nota: o alt é um atributo da tag <img>, não uma tag própria) Fornece uma descrição textual de uma imagem para leitores de tela e motores de busca quando ela não pode ser vista.
    . <label> Ela tem a função específica de criar um rótulo de texto descritivo associado a um controle de entrada

- Quais Media Queries foram implementadas
    . Celular (telas até 425px): Deixa o menu em pé (uma opção embaixo da outra), coloca as notícias em uma única coluna comprida e faz o formulário ocupar a largura inteira da tela para facilitar o toque e a digitação em dispositivos móveis.
    . Tablet (telas entre 426px e 1023px): Coloca o menu deitado e centralizado na tela. Como há mais espaço horizontal, organiza as notícias divididas em 2 colunas lado a lado.
    . Computador (telas a partir de 1024px): Aproveita as telas grandes de monitores para espalhar as notícias em 3 colunas lado a lado, preenchendo melhor o espaço e melhorando a leitura.

- Quais decisões de UX e UI foram adotadas
    Implementação de uma identidade visual única, consistente e acessível através de paleta de cores e uso de favicon. Há forte consistência no layout de todas as páginas e uma hierarquia visual clara, com foco principal no conteúdo lido e depois nas sugestões de leitura. As áreas de cada notícia estão bem separadas por espaçamentos para evitar sobrecarga cognitiva, mantendo a tela limpa e livre de poluição visual. O sistema de navegação é simples, intuitivo e eficiente. A interface se torna memorável pelo contraste bem aplicado, conta com um sistema que previne erros no formulário (através da validação em JS) e gera alta satisfação visual para o usuário.
