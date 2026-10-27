# Third Brain — landing page conceitual

Landing page estática para a ideia de um assistente local de captura, transcrição, organização e busca de anotações.

**Estado:** apresentação visual, não aplicação. O repositório contém apenas `index.html` e `app-icon.png`; as animações são demonstrativas e não executam transcrição, IA, armazenamento ou busca.

## Executar

```bash
python -m http.server 8000
```

Abra `http://localhost:8000`.

## O que a página apresenta

- captura rápida por atalho;
- transcrição local com Whisper;
- enriquecimento com Phi-3;
- tags e conexões entre notas;
- lista de espera externa.

Esses itens descrevem a proposta. Eles não são implementados neste repositório.

## Limitações

- o selo “Em Produção” e alegações de milissegundos/offline não possuem evidência aqui;
- dependências visuais são carregadas por CDN;
- não há build, testes, acessibilidade validada ou deploy documentado;
- o link “Ver no GitHub” aponta para este mesmo repositório, não para o código do produto.

O código experimental relacionado está em [thirdbrain-core](https://github.com/lucasvidalsilva/thirdbrain-core), que também deve ser tratado como protótipo.
