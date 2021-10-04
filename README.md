# pokedex-cli-demo

![Image of Cubone](https://emojis.slackmojis.com/emojis/images/1619172676/32761/cubone.gif)
An example CLI application powered by PokeAPI

## Instructions

Initialize the module

```Bash
go mod init pokedex-cli-demo
```

Install cobra library

```Bash
go get -u github.com/spf13/cobra/cobra
```

Initialize the cli scaffolding

```Bash
cobra init --pkg-name pokedex-cli-demo
```

Install CLI tool

```Bash
go install pokedex-cli-demo 
```

## References

[PokeAPI](https://github.com/PokeAPI/pokeapi/) - A RESTful API for Pokémon

[Cobra](https://github.com/spf13/cobra) - A Commander for modern Go CLI interactions
