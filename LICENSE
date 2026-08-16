# foco

Temporizador Pomodoro simples, feito com HTML, CSS e JavaScript puro — sem dependências, sem build, sem servidor.

## Rodando localmente

Basta abrir o `index.html` no navegador. Ou, se preferir um servidor local:

```bash
python3 -m http.server 8000
```

E acesse `http://localhost:8000`.

## Funcionalidades

- Ciclos de foco / pausa curta / pausa longa configuráveis
- Progresso visual em dial circular
- Contagem de pomodoros completados (sementes)
- Beep sonoro e notificação do navegador ao final de cada sessão
- Estatísticas simples salvas no navegador (`localStorage`)

## Estrutura do código

O JavaScript é organizado em três camadas, pensando em facilitar evolução futura:

- **`Storage`** — camada de persistência. Hoje usa `localStorage`; pode ser trocada por chamadas a uma API sem afetar o resto do app.
- **`TimerEngine`** — máquina de estados do temporizador, independente da interface.
- **UI/render** — funções que desenham o estado atual na tela.

## Próximos passos (ideias)

- [ ] Backend em Python (FastAPI) para contas de usuário e sincronização entre dispositivos
- [ ] Histórico de sessões com gráficos
- [ ] Temas customizáveis

## Licença

MIT — veja [LICENSE](LICENSE).