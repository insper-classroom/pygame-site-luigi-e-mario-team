# Kabuto - Landing Page

Site de apresentacao do jogo **Kabuto**, um bullet hell desenvolvido em Python e Pygame para a disciplina de Design de Software do Insper.

## Pagina publicada

A versao preparada para o GitHub Pages esta na pasta `docs`.

Para publicar:

1. Acesse as configuracoes do repositorio no GitHub.
2. Entre em **Pages**.
3. Em **Branch**, selecione `main`.
4. Na pasta, selecione `/docs`.
5. Salve as configuracoes.

Depois disso, a pagina ficara disponivel no endereco do GitHub Pages do repositorio.

## Estrutura do repositorio

```text
.
├── index.html
├── reset.css
├── style.css
├── assets/
│   ├── Img/
│   ├── Sprites/
│   ├── StoryBoards/
│   └── video/
├── docs/
│   ├── index.html
│   ├── reset.css
│   ├── style.css
│   └── assets/
├── avaliacao_crap_realizada/
└── avaliacao_crap_recebida/
```

## Conteudo da landing page

A pagina inclui:

- Titulo do projeto;
- Descricao do jogo;
- Capturas de tela;
- Nomes dos membros do grupo;
- Log de desenvolvimento;
- Link para download do pacote ZIP do jogo;
- Instrucoes para executar o jogo;
- Area para video curto de apresentacao;
- Esbocos em papel;
- Relato dos principios CRAP.

## Video de apresentacao

O HTML procura o video em:

```text
assets/video/kabuto-demo.mp4
```

Para a versao publicada, o mesmo arquivo tambem deve existir em:

```text
docs/assets/video/kabuto-demo.mp4
```

Se a gravacao estiver em outro formato, como `.mkv`, converta ou exporte para `.mp4` e use esse nome.

## Como executar o jogo

1. Baixe o ZIP pelo link da pagina.
2. Extraia os arquivos.
3. Abra um terminal na pasta do jogo.
4. Instale o Pygame:

```bash
pip install pygame
```

5. Execute o arquivo principal:

```bash
python main.py
```

## Tecnologias

- HTML puro;
- CSS puro;
- Python;
- Pygame.
