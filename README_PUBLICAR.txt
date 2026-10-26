RUMO — DEMONSTRAÇÃO WEB 1.2 | GUIA RÁPIDO

Este ZIP contém a versão WEB (não Android) pronta para o GitHub Pages.
Sugerimos um repositório SEPARADO do repositório Android para não publicar
acidentalmente códigos/arquivos que não precisam ser públicos.

1. Entre no GitHub > New repository e crie `rumo-web-demo` (Public).
2. Acesse o repositório > Add file > Upload files.
3. Extraia o ZIP em seu computador e envie os arquivos DO CONTEÚDO da pasta:
   index.html, manifest.webmanifest, sw.js, .nojekyll e pasta icons/.
   Nao envie apenas o arquivo ZIP. Confirme que index.html está na raiz.
4. Faça commit.
5. No repositório, Settings > Pages > Build and deployment.
   Source: Deploy from a branch; branch: main; folder: /(root); Save.
6. Aguarde a publicação e clique em `Visit site` na seção Pages.
   O link terá formato https://SEU_USUARIO.github.io/rumo-web-demo/

IMPORTANTE: o endereço acima é só um MODELO, não é um link ativo até publicar.

O aplicativo web permite testar calendário, temas e check-ins; lembretes
push do Android NÃO funcionam na versão do navegador.
A demonstração é para ADULTOS com DADOS FICTÍCIOS: os dados ficam no localStorage
sem criptografia de repouso. Não há coleta automática de feedback.
Não inclua históricos de pessoas reais nem arquivos pessoais no repositório.
