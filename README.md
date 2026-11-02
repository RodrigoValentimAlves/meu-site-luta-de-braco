# Site de Rodrigo Valentim Alves

Site oficial sobre a trajetória de Rodrigo Valentim Alves na luta de braço, com informações sobre sua carreira como atleta, técnico e árbitro.

## Conteúdo

- Biografia e principais conquistas.
- Perfil de atleta, técnico e árbitro.
- Carrossel de fotos e galeria de certificados.
- Histórico de títulos e colocações.
- Links para entrevistas, matérias e redes de contato.
- Botão no cabeçalho para alternar entre português e inglês.

## Como abrir o site

O projeto é estático e não precisa instalar dependências ou executar um processo de build.

1. Abra a pasta do projeto no VS Code.
2. Abra `index.html` diretamente no navegador ou use a extensão **Live Server** e clique em **Go Live**.

O botão de tradução e recursos externos, como fontes e ícones, precisam de conexão com a internet.

## Estrutura do projeto

```text
.
├── index.html       # Conteúdo e estrutura das páginas
├── style.css        # Estilos e layout responsivo
├── imagens/         # Fotos da carreira e das competições
└── certificados/    # Certificados, classificações e convocações
```

## Atualizar conteúdo e imagens

- Edite os textos, links e seções em `index.html`.
- Altere cores, espaçamentos e apresentação visual em `style.css`.
- Para trocar a imagem de fundo da seção principal, edite a URL `background` da regra `.hero` em `style.css`.
- Ao adicionar imagens, coloque os arquivos na pasta apropriada e atualize o caminho e o texto alternativo (`alt`) do elemento `<img>` correspondente em `index.html`.

Mantenha os nomes e caminhos dos arquivos exatamente iguais aos referenciados no HTML, incluindo maiúsculas, minúsculas e extensões.
