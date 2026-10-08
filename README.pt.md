# Cola de referência: superpoderes do terminal · Terminal Superpowers

> 🌍 [中文](README.md) · [Español](README.es.md)

Uma **cola de uma página só** com as ferramentas de terminal que realmente valem a pena em 2026: 14 ferramentas, e cada entrada responde a apenas quatro perguntas — **o que ela faz, como instalar, um comando para testar na hora e etiquetas de uso**. Sem enrolação.

## Para quem é

Para engenheiros de operações (SRE/DevOps), desenvolvedores backend e qualquer pessoa que more dentro do terminal. Se você ainda trabalha no `cd`, `ls`, `cat` e `grep` puros, esta cola economiza meia hora do seu dia.

## Como usar

1. Vá direto ao **[CHEATSHEET.md](CHEATSHEET.md)** — o corpo da referência, legível para desenvolvedores de qualquer idioma.
2. Comece pelo "pacote inicial", um único comando (macOS / Homebrew):
   ```bash
   brew install zoxide fzf fd ripgrep eza bat starship lazygit tldr btop tmux zellij
   ```
   No Debian/Ubuntu, a maioria também instala com `sudo apt install <nome>`.
3. Para cada ferramenta, rode o comando de "teste": em cinco minutos você sabe se ela fica.

## O que está incluído

| Categoria | Ferramentas |
|---|---|
| 🆕 Novidades de 2026 | cmux (terminal feito para agentes de IA), yoinks (baixar vídeos sem sair do terminal) |
| 🧭 Navegação e busca | zoxide (`cd` inteligente), fzf (busca difusa), fd (substituto do `find`), ripgrep (substituto do `grep`) |
| 🖥️ Multiplexadores e prompt | tmux (o multiplexador clássico), zellij (workspace moderno de terminal), starship (prompt inteligente) |
| 📄 Ver arquivos | eza (substituto do `ls`), bat (substituto do `cat`) |
| 🛠️ Fluxo de desenvolvimento | lazygit (git visual no terminal), tldr (ajuda rápida de comandos) |
| 📊 Monitoramento | btop (monitor de recursos) |

Todos os links oficiais e do GitHub foram verificados, e os comandos de instalação são reais e funcionais.

## Por que estas 14

- **Novidades de 2026**: cmux e yoinks são ferramentas novas que decolaram este ano no GitHub e resolvem problemas novos da era da programação com IA.
- **Clássicos**: as outras 12 provam seu valor há anos; cada uma substitui um velho comando Unix por algo muito mais rápido e muito mais legível.

## Contribuições são bem-vindas

Conhece uma ferramenta melhor, achou um comando errado ou uma tradução a melhorar? *Pull requests* são bem-vindos. Mantenha o formato de cada entrada (o que faz / instalação / teste / etiquetas) e **verifique se os links funcionam antes de enviar**.

## Licença

MIT © 2026 Guangyi Zhao. Veja [LICENSE](LICENSE).
