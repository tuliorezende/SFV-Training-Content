# Motivação
A ideia é criar um documento para cada boneco com algumas coisas básicas para jogar contra como:
- Framedatas negativas que não se pode deixar passar
- Algumas pressões classicas

# Importante
- Apesar dos movimento serem negativos, é importante ter em mente que nem todos os personagens irão punir, então vale o treino de acordo com o personagem utilizado.

## Blockstuns e Cancels
- Um conceito interessante que pode ajudar a interromper algumas pressões, é como o conceito de blockstun e cancelamento funciona. Trocando uma ideia sobre alguns cenários com o [Keoma](https://twitter.com/Keoma89), ele me explicou que o blockstun (temos que ficamos "presos" após receber um hit) é de 15F. A partir desse número e do startup do special que está sendo feito (ou cancelado) sabemos se podemos interromper ou não
- Exemplos:
    - Personagem X tem contato com o oponente e aplica blockstun de 15F, no frame seguinte, ele cancelou em movimento Y que tem startup 14F isso é true blockstring;
    - Personagem X tem contato com o oponente e aplica blockstun de 15F, no frame seguinte, ele cancelou em MP inferno que tem startup 16F isso não é true blockstring, tendo gap de 1F;
- Essa ideia será importante em alguns cenários (Como M.Bison)

Podemos ter uma espécie de fórmula para tentar identificar o valor de gap
```math
                gap = startup - blockstun + X
```
onde:
- startup: startup do special move;
- blockstun (**15F**);
- X: caso algum personagem não possa cancelar no primeiro frame ativo, essa "diferença deve ser adicionada para se saber o gap;

# Characters
* [Abigail](Abigail.md)
* [Akira](Akira.md)
* [Akuma]()
* [Alex]()
* [Balrog]()
* [Birdie]()
* [Blanka]()
* [Cammy]()
* [Charlie Nash]()
* [Chun-Li](Chun-li.md)
* [Cody]()
* [Dan](Dan.md)
* [Dhalsim]()
* [E. Honda]()
* [Ed]()
* [Eleven]()
* [F.A.N.G]()
* [Falke]()
* [G]()
* [Gill]()
* [Guile]()
* [Ibuki]()
* [Juri Han]()
* [Kage]()
* [Karin]()
* [Ken Masters]()
* [Kolin](Kolin.md)
* [Laura](Laura.md)
* [Lucia]()
* [Luke]()
* [M. Bison](M-Bison.md)
* [Menat]()
* [Necalli]()
* [Oro]()
* [Poison]()
* [R. Mika]()
* [Rashid]()
* [Rose]()
* [Ryu]()
* [Sagat]()
* [Sakura]()
* [Seth]()
* [Urien](Urien.md)
* [Vega]()
* [Zangief]()
* [Zeku]()