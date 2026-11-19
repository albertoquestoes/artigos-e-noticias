# Alberto Questões e Notícias — versão estática inicial

Esta pasta contém uma primeira conversão do conteúdo exportado do WordPress para HTML estático, destinada ao GitHub Pages.

## Conteúdo incluído
- Artigos publicados e páginas publicadas.
- Categorias e tags efetivamente associadas aos artigos exportados.
- Pesquisa local por título e texto.
- Arquivos por ano.
- Sitemap ainda não incluído porque o endereço final do GitHub Pages depende do nome de usuário e da configuração do repositório.

## Publicação
1. Crie ou abra o repositório `albertoquestoesenoticias` no GitHub.
2. Envie **todo o conteúdo desta pasta**, incluindo `index.html`, `assets/`, `search-index.json`, `categorias/`, `tags/`, os diretórios de artigos e os arquivos auxiliares.
3. Nas configurações do repositório, em Pages, selecione a publicação a partir da branch principal e da pasta raiz (`/(root)`).
4. Aguarde a publicação e teste a página inicial, a pesquisa, algumas categorias e artigos.

## Importante antes de considerar a migração concluída
- Esta é uma versão inicial de validação, não uma substituição final do WordPress.
- O XML não informa com segurança a estrutura original de links permanentes. Os artigos foram publicados em diretórios com seus slugs (`/slug/`). Se a estrutura antiga era diferente, será necessário ajustar os caminhos ou criar redirecionamentos.
- As imagens foram intencionalmente omitidas. O texto alternativo foi mantido como nota textual quando havia descrição.
- Links internos identificados foram convertidos para caminhos relativos; links internos sem correspondência foram marcados como `#` e precisam de revisão.
- Metadados específicos de SEO (Yoast/Rank Math), menus e comentários não foram integralmente reproduzidos nesta primeira versão.
- Não há domínio personalizado configurado. O site usa links relativos para funcionar em um projeto GitHub Pages.
- Antes de divulgar o endereço, é importante revisar a página de contato e a política de privacidade, pois podem conter referências ao domínio e aos serviços antigos.

## Limite de tamanho
A versão foi montada sem imagens. Confira o tamanho do repositório antes de publicar; o limite de 1 GB é uma restrição relevante, mas manter o projeto bem abaixo dele é recomendável.
