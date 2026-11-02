# Marcelo Viagens — página de divulgação

Página responsiva para divulgar fretamento, turismo regional e viagens em grupo saindo de Palmas - TO. A versão atual usa fotos reais da van fornecidas pelo proprietário, com recortes feitos para remover interfaces de Instagram/WhatsApp.

## Conteúdo

A página apresenta veículos novos, conforto & segurança, bancos reclináveis, Starlink, fretamento, turismo, montagem de grupos de viagem, turismo regional e a informação de serviço autorizado ANTT. A galeria usa seis fotos locais selecionadas e abre as imagens em tamanho maior.

O formulário reúne nome, telefone, origem, destino, datas, quantidade de passageiros, tipo de viagem e detalhes. Ao enviar, prepara uma mensagem para o WhatsApp configurado no próprio `index.html`; o site não armazena os dados.

## Publicar

O projeto é estático e pode ser publicado no GitHub Pages ou importado na Vercel. Não necessita de banco de dados, build ou dependências externas. Basta servir a raiz do repositório como diretório público.

## Configurar WhatsApp

No arquivo `index.html`, localize `const WHATSAPP_MARCELO` para trocar o número. Use o número completo com DDI e DDD, somente dígitos.
