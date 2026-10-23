# Bestiário de Equestria

Projeto acadêmico em HTML e CSS simples, sem JavaScript, dependências ou build.

## Como abrir e testar

1. Abra index.html com dois cliques ou use “Abrir com” e escolha seu navegador.
2. Clique em “Conhecer as criaturas” para abrir o catálogo.
3. Abra as quatro fichas e teste “Voltar ao catálogo”, “Início” e “Sobre”.
4. Use Tab e Enter para navegar pelo teclado. O primeiro link permite pular ao conteúdo.
5. Diminua a janela ou use o modo de dispositivo do navegador (320, 375 e 768 pixels). Os cartões devem se organizar sem rolagem horizontal.
6. Os links de fontes exigem internet; as páginas do projeto funcionam offline.

## Arquivos

- index.html: página inicial original, com links acrescentados para o catálogo e fichas.
- catalogo.html: lista das quatro criaturas e acesso às fichas.
- windigos.html: descrição, características, habilidades, aparição e fonte de Windigos.
- changelings.html: mesma estrutura para Changelings.
- timberwolves.html: mesma estrutura para Timberwolves.
- cockatrice.html: mesma estrutura para Cockatrice.
- style.css: estilos compartilhados; mantém as cores e classes originais e acrescenta foco de teclado e ajustes para celular.
- README.md: instruções de uso, organização e registro das fontes.
- imagens/changelings.png: ilustração local de Changeling, usada na página inicial, catálogo e ficha.
- imagens/windigos.png: ilustração de Windigo por HerrMyrddin, nas mesmas três posições.
- imagens/cockatrice.png: ilustração de Cockatrice por Flizzick, nas mesmas três posições.
- imagens/timberwolves.png: original enviado pelo usuário, preservado como referência.
- imagens/timberwolves-transparente.png: versão com fundo removido, usada na página inicial, catálogo e ficha.
- imagens/CREDITOS.md: origem, autoria, licença, condições e imagens pendentes.

Para editar um texto, abra o HTML correspondente em um editor. Para mudar o visual de todas as páginas, edite style.css. Mantenha todos os arquivos na mesma pasta.

## Fontes e limites da consulta

Consulta em 22/10/2026. A abertura direta das quatro páginas retornou bloqueio (402/robots.txt). Foi possível ler os textos indexados dessas mesmas páginas na busca. As fichas usam resumos curtos desse material, sem informações acrescentadas por suposição.

- Windigos: https://mlp.fandom.com/wiki/Windigos
- Changelings: https://mlp.fandom.com/wiki/Changelings
- Timberwolves: https://mlp.fandom.com/wiki/Timberwolves
- Cockatrice, pelo episódio: https://mlp.fandom.com/wiki/Stare_Master

Pendente antes da entrega: conferir manualmente a versão integral e atualizada das quatro fontes, incluindo as descrições e aparições resumidas. A wiki é uma fonte comunitária, não documentação oficial da série. Os nomes dos episódios foram mantidos em inglês.

Foi adicionada uma ilustração de Changeling por Durpy, com licença declarada CC BY-NC 3.0, caminho relativo e texto alternativo. Os créditos e links de origem/licença aparecem junto à imagem. Não foram usadas fontes tipográficas externas nem pesquisas com usuários. O projeto não foi publicado nem enviado ao GitHub.

## Imagens e conferência adicional das fontes

A imagem foi obtida da página https://www.deviantart.com/durpy/art/Changeling-vector-297907835 e inspecionada. O CSS usa object-fit: contain para não cortar nem deformar a ilustração. Os links “Ver ficha” continuam com margin-top: auto; a regra foi limitada aos links diretos do cartão para não afetar os créditos.

Uma busca adicional localizou e permitiu baixar Windigo, de HerrMyrddin (CC BY-NC-ND 3.0), e Cockatrice, de Flizzick (CC BY 3.0). As licenças foram conferidas nas páginas originais, e as imagens foram inspecionadas e adicionadas à página inicial, catálogo e respectivas fichas. Os arquivos não foram editados nem cortados. Cada utilização tem texto alternativo, crédito e links de origem e licença.

A imagem de Timberwolves foi fornecida pelo usuário e adicionada à página inicial, ao catálogo e à ficha, com caminho relativo e texto alternativo. Usa o mesmo CSS das demais: 180 px de altura nos cartões e limite de 360 px na ficha, sem deformação ou corte. O original com fundo branco foi preservado como referência. A versão exibida é imagens/timberwolves-transparente.png, com fundo removido pela ferramenta de edição de imagens e canal alfa real, verificado por leitura dos pixels. Não foram adicionados filtros ou modos de mistura ao CSS. Sua autoria, página original e licença continuam sem confirmação; o fornecimento do arquivo não foi registrado como prova de licença. Os detalhes estão em imagens/CREDITOS.md.

As quatro fontes das fichas foram novamente conferidas pelo texto indexado da busca em 22/10/2026. O material encontrado sustenta as descrições já usadas: espíritos de inverno e nevascas (Windigos), mudança de aparência e alimentação por amor (Changelings), corpo de madeira e perseguição (Timberwolves), aparência híbrida e petrificação em Stare Master (Cockatrice). As limitações da consulta estão registradas apenas neste README. As notas sobre busca e bloqueios foram retiradas das páginas para não misturar o conteúdo do site com o processo de pesquisa. Isso não significa que as fontes tenham sido consultadas integralmente.

Para Timberwolves, foram conferidos o artigo da criatura e o resumo de https://mlp.fandom.com/wiki/Spike_at_Your_Service. O resumo descreve os fragmentos de três criaturas se reunindo magicamente em um lobo maior e a ajuda de Spike a Applejack. A reconstrução corporal e essa aparição foram acrescentadas à ficha, com o link adicional. Não foi feita uma revisão audiovisual do episódio.

## Verificação técnica

Os cartões do catálogo e da página inicial usam flex-direction: column e margin-top: auto nos links para alinhá-los na parte inferior de cada linha.

Após esse ajuste, os quatro arquivos de ficha foram lidos: cada link do catálogo corresponde ao título da criatura esperada, e todos os links “Voltar ao catálogo” apontam para catalogo.html, que existe. Essa foi uma conferência dos arquivos, não um teste de cliques em navegador. As regras de reorganização dos cartões também foram conferidas no CSS.

Foram conferidos os destinos dos links locais e âncoras, o idioma, a configuração de viewport, o título principal único e as seções obrigatórias das fichas. O CSS foi revisado para quebra de linha no menu, cartões flexíveis e uma coluna em telas até 600 pixels.

A ferramenta de navegador bloqueou a abertura do endereço local file:// por política de segurança. Portanto, a inspeção visual em navegador e celular ficou pendente. Use os passos de teste acima para concluir essa conferência; a revisão do código não substitui essa inspeção.

Na revisão final, o usuário confirmou que abriu as quatro fichas e que a navegação funcionou. A conferência de caminhos e acessibilidade no código foi repetida. Todos os links usam elementos a com href, sem tabindex negativo ou ocultação que os retire da navegação; a regra a:focus-visible fornece o contorno de foco. Ainda é necessário conferir visualmente as seis páginas em larguras pequenas e percorrer os links com Tab, Shift+Tab e Enter no navegador.


## Revisão dos textos

Os textos das seis páginas foram simplificados, sem acrescentar fatos sobre a série. As descrições dos cartões e os textos alternativos foram padronizados. Os links das fontes e os créditos das imagens foram preservados. A autoria, a fonte original e a licença da imagem dos Timberwolves continuam pendentes em imagens/CREDITOS.md. Antes da entrega, conferir o conteúdo integral e atualizado das quatro fontes e do resumo de Spike at Your Service.
