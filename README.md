# Pokédex Collector

App web (PWA) para completar a Pokédex em cartas Pokémon TCG: marca que Pokémon já tens,
regista *qual* carta tens em cada um, e vê todas as outras cartas desse Pokémon ordenadas
por valor de mercado (€) para saberes que upgrades valorizam a coleção.

- **Dados das cartas:** [TCGdex](https://tcgdex.dev) (GraphQL, grátis)
- **Preços:** Cardmarket (via TCGdex)
- **Imagens dos Pokémon:** [PokéAPI](https://pokeapi.co)
- Funciona offline, instala-se no ecrã principal do iPhone (Adicionar ao Ecrã Principal).
- A coleção fica guardada **no próprio dispositivo** (localStorage); há backup exportar/importar.

Sem framework, sem servidor — só HTML/CSS/JS estático.
