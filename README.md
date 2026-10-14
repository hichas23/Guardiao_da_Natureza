# Guardião da Natureza — Protótipo Web

Primeiro protótipo jogável da Fase 1: **Amazônia em Chamas**.

## Como executar
1. Extraia a pasta `Guardiao_da_Natureza`.
2. Abra `index.html` no navegador. Para desenvolvimento, é recomendado usar a extensão **Live Server** no VS Code.
3. No computador: `A`/`D` ou setas para andar, `Espaço`/`W`/`↑` para pular, `E` para interagir.
4. No celular: use o joystick virtual e os botões **PULAR** e **USAR**.

## Objetivo da fase
1. Inicie a missão.
2. Vá até a mangueira e pressione `E` ou toque em **USAR** perto dela.
3. Aproxime-se de cada um dos três focos de incêndio e use a mangueira.
4. Apague os três focos para concluir a missão.

## Estrutura
- `index.html`: interface e estrutura.
- `style.css`: visual responsivo para celular e computador.
- `game.js`: lógica de movimento, câmera, coleta, interação e conclusão.
- `assets/personagens/`: artes finais dos personagens.
- `assets/cenarios/`: fundos e cenários.
- `assets/itens/`: mangueira, cristais e itens.

## Substituir os desenhos temporários pelas artes
Algumas artes de referência já foram reunidas em `assets`:
- `assets/cenarios/amazonia-fase-1.png`
- `assets/personagens/guia-sprites-kai-animais.png`
- `assets/personagens/sprites-kai-aliados.png`
- `assets/ui/atlas-ui-jungleira.png`

São pranchas completas, então ainda precisamos recortar os sprites individuais e integrar o cenário de forma adequada. Por enquanto, o protótipo usa desenhos temporários para testar a jogabilidade. Consulte `ASSETS_CATALOG.md`.

Sugestão de nomes:
- `assets/personagens/kai.png`
- `assets/personagens/carlos.png`
- `assets/personagens/lumi.png`
- `assets/cenarios/amazonia-fase-1.png`
- `assets/itens/mangueira.png`
- `assets/itens/cristal-verde.png`

## Próximas etapas
1. Integrar as artes finais e sprites animados.
2. Ajustar os controles e obstáculos à arte definitiva.
3. Adicionar diálogos e a escolha de prioridade da fase.
4. Implementar energia/perigos e salvar progresso.
5. Construir as fases 2–6 e o chefe final.
