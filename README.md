# Raquel Tasks

Projeto PWA de lista de tarefas.

## Autor
Raquel

## Atividades

1. **Organização de pastas**  
   Separei CSS em `css/estilo.css`, JS em `js/app.js` e movi ícones para `img/`. Corrigi caminhos em `index.html`, `manifest.json` e `sw.js`.

2. **Identidade própria**  
   Alterei nome para "Raquel Tasks", personalizei cores (#4CAF50) e ajustei `theme-color` e `manifest.json`.

3. **Contador de pendentes**  
   Adicionei `<span id="contador">` no cabeçalho e atualizo com `tarefas.filter(t => !t.feita).length`.

4. **Botão limpar concluídas**  
   Criei botão "Limpar concluídas" com confirmação. Só aparece se houver tarefas concluídas.

5. **Data de criação**  
   Cada tarefa guarda `data` com `new Date().toLocaleDateString('pt-BR')`. Exibida em `<small>` abaixo do texto. Tratamento para tarefas antigas sem data.

## Como rodar
```bash
python -m http.server 8000
