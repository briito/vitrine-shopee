# Vitrine Shopee — Radar F5 Shop

Projeto estático em HTML, CSS e JavaScript, sem backend, banco de dados ou build.

## Como usar

1. Abra `index.html` no navegador ou publique a pasta na Vercel.
2. Edite `assets/products.js` para cadastrar, alterar ou excluir produtos.
3. Para cada produto, informe `id`, `nome`, `preco` (número, ex.: `39.90`), `categoria`, `imagem`, `link` de afiliado HTTPS e `destaque` (true/false).
4. Salve as imagens em `assets/imagens/` (crie a pasta se necessário) e informe o caminho relativo correto.
5. Faça commit e push no seu clone Git original; a Vercel publicará se o deploy automático estiver configurado.

O array `PRODUTOS` começa vazio de propósito: nenhum produto, preço ou link fictício será publicado. O estado vazio é mostrado ao visitante até o primeiro cadastro. Categorias são definidas em `CATEGORIAS` no mesmo arquivo. Os botões de categoria filtram os cards localmente.

## Avisos e páginas institucionais

Os cards exibem aviso de variação de preços. O rodapé contém avisos de preços e comissões de afiliados. As páginas em `legal/` são **textos-base que precisam ser revisados antes da publicação definitiva**, especialmente identificação e contato do responsável, práticas reais de privacidade e conformidade com políticas aplicáveis. O site usa Google Fonts, que realiza requisições a serviço externo. Para dispensar essa dependência, remova a linha `@import` do CSS; o fallback Arial continuará funcionando.

## Estrutura

- `index.html`: página pública
- `assets/styles.css`: estilos responsivos
- `assets/products.js`: catálogo editável manualmente
- `assets/app.js`: filtros, renderização e links
- `legal/*.html`: páginas institucionais preliminares

## Git

Este ZIP de entrega não inclui `.git`. Extraia/copiei os arquivos para a pasta do clone existente para manter seu histórico Git e publicar normalmente.
