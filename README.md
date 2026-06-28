# Biblioteca Juliano/Ana Clara — APP V1

Versão funcional em HTML/CSS/JS + Supabase + PWA.

## O que esta versão faz

- Catálogo de livros compartilhado.
- Controle individual para Juliano, Ana Clara e Daine.
- Campos por pessoa: lido, favorito, nota, datas e comentário.
- Dashboard por leitor.
- Filtros por busca, tema, leitor, status e ordenação.
- Cadastro, edição e exclusão de livros.
- Exportação JSON e CSV.
- PWA instalável no celular depois de publicado em HTTPS.

## Como configurar o Supabase

1. Abra seu projeto no Supabase.
2. Vá em **SQL Editor > New query**.
3. Abra o arquivo `supabase/01_schema.sql`, copie tudo, cole e clique em **Run**.
4. Depois abra `supabase/02_seed_livros.sql`, copie tudo, cole e clique em **Run**.

A base inicial é carregada direto pelo SQL, evitando travamento no navegador.

## Como testar no computador

Depois de rodar os SQLs:

1. Abra `index.html` no navegador.
2. O app deve mostrar a mensagem: `Sincronizado. 162 livros carregados.`

Se quiser testar como app/PWA, publique na Vercel ou Netlify, porque o modo instalável exige HTTPS.

## Como publicar grátis na Vercel

1. Crie uma conta em https://vercel.com usando GitHub.
2. Crie um repositório no GitHub com estes arquivos.
3. Na Vercel, clique em **Add New > Project**.
4. Escolha o repositório.
5. Como é HTML simples, não precisa configurar build.
6. Publique.

Depois você terá um link para enviar pelo WhatsApp.

## Como instalar no Android

1. Abra o link publicado no Chrome do celular.
2. Toque nos três pontos.
3. Toque em **Adicionar à tela inicial** ou **Instalar app**.

## Observação importante

Esta V1 é sem login. Qualquer pessoa com o link consegue visualizar e editar. É simples e prático para uso familiar. Em uma próxima versão, dá para incluir login por usuário.
