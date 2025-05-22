# slitherio-simple-bot
- Aluno: Ricardo Moreira Gomes.
- Descrição: Repositório para a entrega do Trabalho do Grau A, Inteligência Artificial 2025/1 - Unisinos.

### 🕹️ Sobre o Projeto
Este repositório contém todos os arquivos necessários para executar a Atividade Final de Grau A da cadeira de Inteligência Artificial 2025/1 = Unisinos. O projeto foi desenvolvido na Unity 6 e, caso deseje conferir instruções mais detalhadas, consulte o [README.md](https://github.com/fellowsheep/IAJogos-20251/blob/main/AISnakeBot2025/README.md) elaborado pela Professora Rossana. A ideia é ser um framework simplificado de Slither.io com a produção de bots específicos por cada aluno.

### 🐍 Ricardobot.cs
Meu bot foi desenvolvido com os steering behaviors Seek, Wander e Obstacle Avoidance. Além disso, ele combina esses comportamentos com pesos diferentes possuindo uma "árvore" de decisão dependendo da situação (é um bot reativo, afinal). Ele também possui um comportamento mais agressivo de flanqueamento para poder eliminar adversários. Quando atinge o tamanho de 20 unidades, ele deixa de buscar por mais orbs e passa apenas a caçar outras cobras.

### 📁 Estrutura do Projeto
```text
slitherio-simple-bot/
├── .vscode
├── Assets/
│   ├── Prefabs
│   └── Scenes/
│       └── SampleScene.unity (cena principal)
│   └── Scripts/
│       └── Behaviours/
│           ├── AIBehaviour.cs
│           ├── Dumb.asset
│           ├── Dummy.cs
│           ├── Playerbot.cs
│           ├── Playerbot_.asset
│           ├── Ricardobot.asset (scriptable object)
│           └── Ricardobot.cs (bot herdado de AIBheaviour desenvolvido como entrega)
│       ├── GameLogic.cs
│       ├── NameBanner.cs
│       ├── OrbBehavior.cs
│       ├── SnakeBody.cs
│       └── SnakeMovement.cs
│   ├── Sprites
│   └── TextMesh Pro
├── Packages
├── ProjectSettings
├── .collabignore
├── .gitattributes
├── .gitignore
├── .vsconfig
└── README.md
```

### 📚 Referências
* Millington, I. (2019). AI for Games (3rd ed.). CRC Press.
* Slither.io: https://slither.io