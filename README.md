# Fulltank+

Site estático, HTML/CSS/JS em dist. Vercel publica dist usando vercel.json.

## Páginas
- `/`: exclusivamente clientes, benefícios, telas reais, simulação por litro e download gratuito.
- `/para-postos`: jornada comercial, retaguarda real, fidelidade e formulário.

## Configuração pendente
Preencher dist/config.js com links oficiais das lojas e WhatsApp comercial. Sem configuração, o site informa o canal pendente; dados do formulário não são enviados nem armazenados. Com WhatsApp, abre mensagem para o usuário confirmar o envio. Não há backend ou analytics.

## Identidade e imagens
Marca oficial preservada. Telas reais do app fornecidas pelo cliente. Dashboard sem email ou lista de dados pessoais. Valores do painel não são promessa de resultado. Fotografia de rotina ilustrativa gerada; não é cliente nem depoimento. Base de mais de 20 mil informada pelo cliente. R$0,10/L é simulação ilustrativa, variável por posto.

## Empresa
Canaã Gestão e Participação Empresarial Ltda — CNPJ 64.343.022/0001-37.
Av. Dep. Esteves Rodrigues, 1121 - Todos Os Santos, Montes Claros - MG, 39400-020.

## Validação
Sintaxe JS, assets e âncoras locais verificados. Prévia desktop e enquadramento mobile de 390px inspecionados no navegador. Troca de telas, calculadora (30L = R$3) e formulário com configuração ausente testados. Animações respeitam preferência de movimento reduzido.

Para servir localmente: `python3 -m http.server 8080 --directory dist`.
