# Pokédex Web App

Este projeto é uma Pokédex interativa desenvolvida para web, que permite ao usuário buscar e navegar por diferentes Pokémon, exibindo informações detalhadas de cada um. Os dados são obtidos em tempo real da [PokéAPI](https://pokeapi.co/).

## 🧩 Funcionalidades

- **Busca por Pokémon**: Pesquise Pokémon pelo nome ou número.
- **Navegação entre Pokémon**: Navegue para o Pokémon anterior ou próximo.
- **Informações exibidas**: Exibe o nome, número e imagem oficial do Pokémon.
- **Música de fundo**: Reproduz uma música de fundo enquanto o usuário explora a Pokédex.

## 🚀 Tecnologias Utilizadas

- **HTML5**: Estrutura da página.
- **CSS3**: Estilos da interface.
- **JavaScript**: Funcionalidades da aplicação e integração com a PokéAPI.
- **PokéAPI**: Fonte de dados dos Pokémon.

## 📂 Estrutura de Arquivos

```
📁 projeto-pokedex
├── 📄 index.html            # Estrutura principal da Pokédex
├── 📁 css
│   └── style.css            # Estilos da Pokédex
├── 📁 js
│   └── script.js            # Lógica JavaScript e integração com a PokéAPI
├── 📁 audio
│   └── background.pokemon.mp3 # Música de fundo
└── 📁 images
    └── pokedex.png          # Imagem da Pokédex
```

## 🎮 Como Usar

1. **Clone o repositório** ou faça o download dos arquivos.
2. **Abra o arquivo** `index.html` no navegador.
3. **Busque por Pokémon** inserindo o nome ou número no campo de pesquisa.
4. **Use os botões "Prev" e "Next"** para navegar entre os Pokémon.

## 🛠️ Implementação

- **HTML**: Estrutura do layout da Pokédex.
- **CSS**: Estilos visuais e responsividade da interface.
- **JavaScript**: 
  - Função `fetchPokemon` para buscar os dados do Pokémon.
  - Função `renderPokemon` para exibir os dados na página.
  - Lógica de navegação entre Pokémon e busca de erro quando não encontrado.

## 📌 Pré-requisitos

- Navegador com suporte a JavaScript e HTML5.
- Conexão com a internet para acessar a PokéAPI.

## 💡 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para sugestões e melhorias.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT.
