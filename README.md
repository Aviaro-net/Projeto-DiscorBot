# 🐺 Wolframium

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Discord.py](https://img.shields.io/badge/discord.py-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)

**Uma caixa de ferramentas completa para RPG de mesa no Discord.**

Fichas dinâmicas · Rolagens inteligentes · Combate automatizado · Geração de conteúdo · Imersão sonora · Play-Solo

</div>

---

## 👥 Desenvolvido por

<div align="center">

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/MarcosMakosu">
        <img src="https://github.com/MarcosMakosu.png" width="100px;" alt="MarcosMakosu"/><br />
        <sub><b>MarcosMakosu</b></sub>
      </a><br />
      <a href="https://github.com/MarcosMakosu">
        <img src="https://img.shields.io/badge/GitHub-MarcosMakosu-181717?style=flat-square&logo=github" />
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/junny11">
        <img src="https://github.com/junny11.png" width="100px;" alt="junny11"/><br />
        <sub><b>junny11</b></sub>
      </a><br />
      <a href="https://github.com/junny11">
        <img src="https://img.shields.io/badge/GitHub-junny11-181717?style=flat-square&logo=github" />
      </a>
    </td>
  </tr>
</table>

</div>

---

## 📖 Sobre o Projeto

**Wolframium** é um bot de Discord pensado para ser o *canivete suíço* de mestres e jogadores de RPG de mesa. Ele centraliza fichas, rolagens, combate, inventário, geração aleatória e imersão em um único lugar — eliminando planilhas externas e reduzindo erros durante a sessão.

O projeto é construído em **Python** com **SQLite** para persistência local, priorizando simplicidade, portabilidade e evolução incremental (MVP primeiro, recursos avançados depois).

---

## 🎯 Objetivos Principais

| # | Objetivo | Descrição |
|---|----------|-----------|
| 1 | 📝 **Fichas Automatizadas** | Criação, edição, arquivamento e exportação (PDF/JSON) por campanha |
| 2 | 🎲 **Rolagens Inteligentes** | Dados complexos que aplicam bônus da ficha automaticamente |
| 3 | 🕓 **Histórico de Alterações** | Rastreabilidade total: quem mudou o quê e quando |

---

## ✨ Funcionalidades

### 📝 Fichas e Personagens
- Templates por sistema: **D&D 5e, Tormenta20, Ordem Paranormal, Cyberpunk RED, Pathfinder, CoC, Vampiro, Fate, PbtA**
- Campos dinâmicos: atributos, perícias, PV, sanidade, mana, spell slots, recursos, condições, inventário
- Múltiplos personagens por usuário · 1 ficha principal por campanha
- Exportação/importação em **JSON** e **PDF**
- Embed resumido com botões rápidos: *Rolar Ataque · Tomar Dano · Descansar · Usar Item*
- Histórico de alterações com autoria e data

### 🎲 Dados e Rolagens
- Rolagens simples e avançadas: `/r 1d20+5`, `/r 2d20kh1`, `/r 4d6dl1`, `/r 10d10>=6`
- Vantagem, desvantagem, dados explosivos, sucessos e falhas críticas
- Rolagens públicas, privadas ou restritas ao mestre
- **Macros de ataque** (ataque + dano + crítico em um clique)
- Suporte a dados especiais: Fome (Vampiro), Sanidade (OP), Caos (Tormenta)

### ⚔️ Combate e Iniciativa
- Iniciativa automática com ordenação e turno atual
- Painel com PV, condições, buffs/debuffs e duração
- Botões: *Próximo Turno · Dano · Cura · Adicionar/Remover Condição*
- HP temporário, morte, ferimentos, exaustão
- Modo "esconder PV dos inimigos" · Log de combate exportável

### 🧙 Ferramentas do Mestre
- Criação/importação de NPCs e monstros com statblock
- Geradores: encontros por nível, loot, tesouro, nomes, tavernas, rumores, quests, masmorras, clima
- **GM Rolls** (rolagens secretas) · Notas de campanha (`/lore [nome]`)
- Facções, reputação, favores e relacionamentos
- Linha do tempo, pistas reveladas e NPCs conhecidos
- Agendamento de sessões, presença, lembretes e **recaps automáticos**

### 🎒 Ferramentas do Jogador
- Inventário com peso, moedas, itens mágicos e charges
- Controle de spell slots, ki, fúria, superioridade, munição
- Descanso curto/longo com recuperação automática
- Diário do personagem · Assistente de level up
- Sistema de downtime (treinamento, pesquisa, crafting, negócios)

### 🏰 Campanha e Sessão
- Canais por campanha: **IC · OOC · Fichas · Combate · Handouts**
- Quadro de missões com status e recompensas
- Calendário, logs e resumo automático da sessão
- Controle de XP e marcos · **Multi-campanha** por servidor
- Backup e restauração

### 🎨 Imersão
- Playlists e trilhas sonoras por cena (seletor por **lugar × tensão**)
- Efeitos sonoros: espada, magia, monstro, taverna
- Comandos narrativos: `/descrever`, `/clima`, `/som`
- Envio automático de imagens de cenário

### 🎭 Play-Solo
- **Mythic GME** · **CRGE** · **One Page Solo Engine**

### 🔌 Integrações
- APIs: **Open5e · D&D 5e API · Pathfinder**
- VTTs: **Roll20 · Foundry · Owlbear Rodeo**
- Google Sheets · Webhooks · Macros personalizadas

---

## 🛠️ Stack Técnica

```
🐍 Python 3.11+       →  Lógica do bot
🤖 discord.py         →  Interface Discord
🗄️ SQLite             →  Persistência local
📄 ReportLab / FPDF   →  Exportação em PDF
🎵 FFmpeg + yt-dlp    →  Áudio e trilhas
```

---

## 🚀 Roadmap (MVP → Completo)

- [x] 🎯 Definição de escopo e arquitetura
- [ ] 🧱 **MVP**: Fichas + Dados + Combate
- [ ] 📊 Sistema de campanhas e permissões
- [ ] 🎲 Macros e rolagens contextuais
- [ ] 🧙 Ferramentas do mestre (geradores + lore)
- [ ] 🎒 Inventário, economia e downtime
- [ ] 🎨 Módulo de áudio e imersão
- [ ] 🎭 Suporte a Play-Solo
- [ ] 🔌 Integrações externas (APIs, VTTs)

---

## 📚 Referências e Inspirações

- [Donjon](https://donjon.bin.sh) · Tome of Adventure Design
- UNE (The Universal NPC Emulator) · The Mother of All Encounter Tables
- [World Anvil](https://www.worldanvil.com/) · [Kanka.io](https://kanka.io/) · LegendKeeper · Notion

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se livre para abrir *issues*, sugerir sistemas/templates ou enviar *pull requests*.

1. Faça um **fork** do projeto
2. Crie uma branch (`git checkout -b feature/minha-feature`)
3. Commit (`git commit -m 'feat: adiciona X'`)
4. Push (`git push origin feature/minha-feature`)
5. Abra um **Pull Request**

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja `LICENSE` para mais informações.

---

<div align="center">

**🐺 Wolframium** — *Role o dado. O resto é com a gente.*

Desenvolvido com 💙 por [**MarcosMakosu**](https://github.com/MarcosMakosu) e [**junny11**](https://github.com/junny11)

⭐ Se este projeto te ajuda, considere dar uma estrela!

</div>

---

### 💡 Dicas rápidas para o GitHub

- **Topo do repo**: adicione um banner/imagem (`assets/banner.png`) e referencie com `![banner](assets/banner.png)`.
- **Badges extras** úteis: `![Último commit](https://img.shields.io/github/last-commit/user/repo)`, `![Issues](https://img.shields.io/github/issues/user/repo)`, `![Stars](https://img.shields.io/github/stars/user/repo)`.
- **Arquivos sugeridos** na raiz: `LICENSE`, `CONTRIBUTING.md`, `CHANGELOG.md`, `.gitignore` (Python), `pyproject.toml` ou `requirements.txt`.
- **Estrutura sugerida**:
  ```
  wolframium/
  ├── bot/
  │   ├── cogs/         # comandos por módulo (fichas, dados, combate…)
  │   ├── database/     # models + migrations SQLite
  │   └── utils/
  ├── assets/           # banner, ícones
  ├── docs/
  ├── tests/
  └── README.md
  ```

---
## 🏆 Contributors

<div align="center"><a href="https://github.com/MarcosMakosu/Wolframium/graphs/contributors"> <img src="https://contrib.rocks/image?repo=MarcosMakosu/Wolframium" /> </a>

  
  

[https://img.shields.io/github/contributors/MarcosMakosu/Wolframium?style=for-the-badge&color=blue](https://img.shields.io/github/contributors/MarcosMakosu/Wolframium?style=for-the-badge&color=blue)  
[https://img.shields.io/github/last-commit/MarcosMakosu/Wolframium?style=for-the-badge&color=green](https://img.shields.io/github/last-commit/MarcosMakosu/Wolframium?style=for-the-badge&color=green)  
[https://img.shields.io/github/issues/MarcosMakosu/Wolframium?style=for-the-badge&color=orange](https://img.shields.io/github/issues/MarcosMakosu/Wolframium?style=for-the-badge&color=orange)  
[https://img.shields.io/github/stars/MarcosMakosu/Wolframium?style=for-the-badge&color=yellow](https://img.shields.io/github/stars/MarcosMakosu/Wolframium?style=for-the-badge&color=yellow)  
[https://img.shields.io/github/forks/MarcosMakosu/Wolframium?style=for-the-badge&color=purple](https://img.shields.io/github/forks/MarcosMakosu/Wolframium?style=for-the-badge&color=purple)

</div>
