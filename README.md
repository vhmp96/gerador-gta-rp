# Gerador de Banner de Procurado - GTA RP

![https://i.postimg.cc/66RxvMXG/gerador.png] (https://postimg.cc/xq0Zryq0)

## 🎯 Objetivo

Este projeto foi criado para solucionar uma necessidade da comunidade de Roleplay (RP), especificamente para jogadores que atuam como policiais em cidades do GTA RP, como a DPC Valley. O objetivo é automatizar e padronizar a criação de banners de "Procurado", eliminando a necessidade de editar imagens manualmente e agilizando a divulgação de informações importantes dentro do jogo.

A ferramenta permite que qualquer usuário crie um banner com aparência profissional em poucos segundos.

## ✨ Funcionalidades Principais

- **Upload de Imagem:** Permite o carregamento da foto do suspeito diretamente do computador.
- **Redimensionamento Automático:** A imagem é automaticamente ajustada e enquadrada para se adequar perfeitamente ao layout do banner.
- **Entrada de Dados:** Campos para inserir o nome completo e o apelido (vulgo) do procurado.
- **Geração Instantânea:** Um clique no botão "Gerar Banner" cria o pôster com as informações preenchidas.
- **Preview em Tempo Real:** O usuário pode visualizar como o banner ficará antes de baixar.
- **Download em Alta Qualidade:** Opção para baixar o banner finalizado no formato PNG, pronto para ser compartilhado.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando tecnologias web front-end padrão:

- **HTML5:** Para a estrutura semântica da página.
- **CSS3:** Para a estilização completa, incluindo o layout flexbox/grid e o tema escuro (dark mode).
- **JavaScript (Vanilla):** Para toda a lógica e interatividade, incluindo:
  - Manipulação do DOM (Document Object Model).
  - Leitura de arquivos de imagem locais com a API `FileReader`.
  - Processamento e renderização de imagens utilizando a **API HTML Canvas**.

## 📖 O que eu aprendi

Este foi um projeto fundamental para solidificar meus conhecimentos em desenvolvimento front-end. Os principais aprendizados foram:

- **Manipulação Avançada do DOM:** Capturar dados de formulários, responder a eventos de clique e carregar imagens dinamicamente.
- **API `FileReader`:** Entender o fluxo de trabalho assíncrono para ler arquivos do sistema do usuário de forma segura.
- **HTML Canvas:** Este foi o maior aprendizado. Aprendi a:
  - Desenhar uma imagem carregada em um elemento `<canvas>`.
  - Adicionar e estilizar múltiplos textos sobrepostos na imagem.
  - Controlar a posição e o alinhamento dos elementos desenhados.
  - Exportar o conteúdo final do canvas como uma imagem `PNG` para download, utilizando o método `toDataURL()`.
- **Melhores Práticas de UX/UI:** Criei uma interface intuitiva, com instruções claras ("Como Usar") para garantir que qualquer pessoa consiga usar a ferramenta sem dificuldades.

## 🚀 Como Usar

O projeto é composto apenas por arquivos front-end e não requer um servidor para ser executado.

1.  Clone o repositório: `git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git`
2.  Navegue até a pasta do projeto.
3.  Abra o arquivo `index.html` em seu navegador de preferência.

[🔗 **Clique aqui para ver uma demonstração ao vivo!**](URL_DO_SEU_PROJETO_ONLINE_AQUI)
