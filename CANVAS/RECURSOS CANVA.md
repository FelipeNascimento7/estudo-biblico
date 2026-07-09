Assumindo que você quis dizer **Canvas do Obsidian** — o quadro visual nativo, não o site Canva.com — estes são os principais recursos nativos disponíveis.

## 1. O que é o Canvas no Obsidian

O **Canvas** é um plugin core do Obsidian para organização visual de notas. Ele permite montar um espaço 2D/infinito com notas, arquivos, anexos, páginas da web, conexões e grupos. Os arquivos Canvas são salvos com extensão **`.canvas`**, usando o formato aberto **JSON Canvas**. ([Obsidian](https://obsidian.md/help/plugins/canvas "Canvas - Obsidian Help"))

---

## 2. Criar um Canvas

Você pode criar um novo Canvas por:

1. **Paleta de comandos**
    
    - `Canvas: Create new canvas`
        
2. **Explorador de arquivos**
    
    - Clique direito em uma pasta
        
    - `New canvas`
        
3. **Ribbon/barra lateral esquerda**
    
    - Ícone de criar novo Canvas
        

---

## 3. Tipos de cards que você pode adicionar

No Canvas, quase tudo é organizado como **cards**.

### 3.1 Card de texto

Card solto, sem ser uma nota do cofre.

Recursos:

- escrever texto direto no Canvas;
    
- usar Markdown;
    
- usar links internos;
    
- usar blocos de código;
    
- editar com duplo clique;
    
- converter o card em uma nota `.md`.
    

Importante: cards de texto puro **não aparecem nos backlinks**. Para aparecerem, precisam ser convertidos em arquivo/nota. ([Obsidian](https://obsidian.md/help/plugins/canvas "Canvas - Obsidian Help"))

### 3.2 Card de nota

Permite adicionar uma nota existente do seu vault ao Canvas.

Você pode adicionar por:

- botão de documento no Canvas;
    
- menu de contexto;
    
- arrastando uma nota do File Explorer.
    

### 3.3 Card de mídia

Você pode adicionar mídias do vault, como:

- imagens;
    
- áudios;
    
- PDFs;
    
- outros tipos de arquivo reconhecidos ou não reconhecidos.
    

### 3.4 Card de página da web

Permite embutir uma página web dentro do Canvas.

Recursos:

- adicionar uma URL manualmente;
    
- arrastar uma URL do navegador para o Canvas;
    
- abrir a página no navegador com `Ctrl`/`Cmd` + clique ou pelo menu de contexto.
    

### 3.5 Card a partir de pastas

Você pode arrastar uma pasta do File Explorer para o Canvas. O Obsidian adiciona os arquivos daquela pasta ao quadro.

---

## 4. Edição de cards

Recursos disponíveis:

- editar cards de texto e notas com duplo clique;
    
- sair da edição clicando fora ou apertando `Esc`;
    
- editar pelo menu de contexto;
    
- excluir cards com `Backspace`, `Delete` ou pelo botão de remoção;
    
- substituir uma nota ou mídia por outra do mesmo tipo usando **Swap file**;
    
- rolar o conteúdo interno de um card depois de selecioná-lo.
    

---

## 5. Seleção e organização

Você pode:

- selecionar um card individual;
    
- arrastar uma caixa de seleção sobre vários cards;
    
- adicionar/remover cards da seleção com `Shift`;
    
- selecionar tudo com `Ctrl+A` ou `Cmd+A`;
    
- mover cards livremente;
    
- duplicar uma seleção com `Alt` ou `Option` enquanto arrasta;
    
- mover apenas em uma direção segurando `Shift`;
    
- desativar o encaixe/snap segurando `Space`;
    
- trazer um card para frente ao selecioná-lo.
    

---

## 6. Redimensionamento

Você pode redimensionar cards arrastando suas bordas.

Atalhos úteis:

- `Space` durante o redimensionamento: desativa o snap;
    
- `Shift` durante o redimensionamento: mantém a proporção do card.
    

---

## 7. Conexões entre cards

O Canvas permite criar linhas entre cards para representar relações.

Recursos:

- conectar dois cards com uma linha direcionada;
    
- criar uma conexão arrastando a bolinha na borda de um card;
    
- criar um novo card a partir de uma conexão solta;
    
- desconectar dois cards;
    
- remover uma conexão;
    
- reconectar uma linha a outro card;
    
- navegar até a origem ou destino da conexão;
    
- adicionar rótulo/label à conexão;
    
- editar o label da conexão;
    
- mudar a cor da conexão.
    

---

## 8. Cores

Você pode alterar a cor de:

- cards;
    
- conexões/linhas.
    

Isso ajuda a criar categorias visuais, prioridades, status ou tipos de relacionamento.

---

## 9. Grupos

O Canvas possui grupos para organizar visualmente cards relacionados.

Recursos:

- criar grupo vazio;
    
- criar grupo a partir de cards selecionados;
    
- mover cards dentro de grupos;
    
- renomear grupo com duplo clique no nome;
    
- usar grupos como áreas visuais para separar temas, etapas, módulos ou ideias.
    

---

## 10. Navegação no Canvas

### 10.1 Pan/mover a tela

Você pode navegar pelo quadro usando:

- `Space` + arrastar;
    
- botão do meio do mouse;
    
- scroll do mouse para mover verticalmente;
    
- `Shift` + scroll para mover horizontalmente.
    

### 10.2 Zoom

Você pode aproximar ou afastar com:

- `Space` + scroll;
    
- `Ctrl`/`Cmd` + scroll;
    
- botões de zoom no canto superior direito.
    

### 10.3 Zoom to fit

Mostra todos os itens do Canvas na tela.

Atalho:

```text
Shift + 1
```

### 10.4 Zoom to selection

Ajusta o zoom para mostrar apenas os itens selecionados.

Atalho:

```text
Shift + 2
```

### 10.5 Reset zoom

Volta o zoom ao nível padrão.

---

## 11. Embed de Canvas em notas

Você pode incorporar um Canvas dentro de uma nota usando a sintaxe padrão de embed do Obsidian.

Exemplo:

```markdown
![[Meu Canvas.canvas]]
```

---

## 12. Formato de arquivo

Cada Canvas é salvo como arquivo:

```text
nome-do-canvas.canvas
```

Internamente, ele usa o formato aberto **JSON Canvas**, o que permite que outros aplicativos ou plugins leiam e manipulem esse tipo de arquivo. ([Obsidian](https://obsidian.md/help/plugins/canvas "Canvas - Obsidian Help"))

---

## 13. Resumo geral dos recursos

|Categoria|Recursos|
|---|---|
|Criação|novo Canvas pela paleta, ribbon ou explorador|
|Cards|texto, notas, mídias, PDFs, áudio, web pages, arquivos de pasta|
|Texto|Markdown, links, código, conversão para nota|
|Organização|mover, duplicar, redimensionar, selecionar múltiplos cards|
|Conexões|linhas direcionadas, labels, reconexão, remoção, navegação origem/destino|
|Visual|cores em cards e conexões|
|Grupos|criar, agrupar cards, renomear, organizar áreas|
|Navegação|pan, zoom, zoom to fit, zoom to selection, reset zoom|
|Integração|embed de Canvas em notas|
|Arquivo|`.canvas` em formato JSON Canvas|

Se você estava falando do **Canva.com integrado ao Obsidian**, não do **Canvas nativo**, aí a resposta muda: o Obsidian não tem uma integração nativa oficial equivalente ao Canva; normalmente a pessoa usa links, embeds web, imagens exportadas ou plugins da comunidade.