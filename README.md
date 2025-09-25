# hdcHost
hDC Host – Site Institucional Responsivo
Descrição
Este projeto é um site institucional para "hDC Host", uma empresa fictícia de hospedagem de sites focada em qualidade e segurança. O design é moderno, responsivo e possui seções para apresentação de serviços, planos de hospedagem, busca de domínio, formulário de contato e redes sociais.

Tecnologias Utilizadas
HTML5

CSS3 (com flexbox e media queries para responsividade)

Ionicons para ícones (importados via CDN)

Estrutura do Projeto
Navbar (Barra de Navegação)
Logomarca à esquerda

Itens do menu à direita: Home, Preços, Contato, Entrar (botão destacado)

Navbar responsiva com layout absoluto dos itens

Banner Principal
Imagem de fundo configurada via CSS

Texto centralizado com título e subtítulo, ambos com sombra para melhor leitura

Seção de Serviços
Três serviços destacados com ícones, título e texto descritivo

Layout em flexbox horizontal que adapta para coluna em telas menores

Seção de Planos
Apresenta 4 planos de hospedagem, cada um com preço, nome e lista de características

Planos apresentados em cards flexíveis com destaque para o plano recomendado

Layout flexível que muda para coluna em dispositivos menores

Busca de Domínio
Formulário simples para pesquisar domínios com input texto e botão de envio estilizados

Contato
Formulário de contato com campos para nome, email e mensagem

Layout centralizado em tela, inputs com borda arredondada

Rodapé
Texto de direitos autorais

Ícones sociais (Facebook, Twitter, Instagram, Linkedin) usando Ionicons

Responsividade
Uso de media queries para diferentes larguras de tela:

Laptops pequenos: ajuste da largura dos containers e margens reduzidas

Telas menores (até 900px): serviços e planos reorganizam-se em coluna

Tablets e dispositivos móveis (até 600px): cards dos planos ficam empilhados e elementos da navbar ajustam posição

Propriedade overflow-x: hidden; sugerida para evitar espaço lateral branco

Como usar
Colocar o código HTML em um arquivo index.html.

Colocar a folha de estilo CSS no arquivo style.css na mesma pasta.

Colocar as imagens na pasta img/ conforme os nomes utilizados (ex: hdchostlogo.png, mainbanner.png).

Acessar o arquivo index.html em qualquer navegador moderno.

Considerações Finais
O site foi desenhado para ser clean, direto e funcional. Pode ser facilmente expandido para incluir mais seções, animações ou integração com backend para busca de domínios e envio de formularios.
