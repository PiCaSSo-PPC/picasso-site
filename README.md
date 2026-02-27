## Estrutura

- Cada página do website é um ficheiro html separado

- Páginas existentes:
    - **index.html**: Visão geral do projeto, contexto e informações importantes
    - **workplan.html**: Descrição das tarefas e objetivos principais
    - **functionalities.html**: Funcionalidades da plataforma com screenshots
    - **team.html**: Descrição dos membros da equipa e parceiros institucionais
    - **events.html**: Workshops, apresentações e outros eventos específicos ao PiCaSSoPiCaSSo
    - **resources.html**: Publicações, apresentações e outros recursos científicos relacionados com os temas de investigação do PiCaSSo
    - **contact.html**: Detalhes de contacto

- CSS personalizado dividido em três ficheiros (dentro de assets/css):
    - **main.css**: definições globais e estilos básicos
    - **components.css**: cards, badges e outros elementos reutilizáveis
    - **sections.css**: regras de layout por secção

- assets/img guarda as imagens que são usadas 

- assets/logo guarda as diferentes versões do logo

## Para fazer mudanças (guia para as mais prováveis)

- **Nova página**: copiar um ficheiro HTML existente; atualizar a tag <title>; acrescentar nova página à secção da navbar, definir o nav-link atual como ativo e mudar a navbar nos outros ficheiros; mudar a informação do header e do div container container-content; deixar o footer igual;

- **Novo membro da equipa**: adicionar um div team-card dentro do team.html seguindo o padrão existente

- **Novo evento ou recurso**: adicionar um div document-card dentro da secção relevante em events.html ou resources.html (se necessário um div documents-section antes)

- **Novo screenshot na página Funcionalidades**: colocar a imagem em assets/img/ e adicionar ou mudar um div screenshot-container em functionalities.html

O site online https://picasso.inesc-id.pt/ é automaticamente atualizado diariamente com o conteúdo da branch main.