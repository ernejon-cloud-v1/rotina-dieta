# Controle de Dieta e Treinos — v2

Arquivos:
- `index.html`: aplicativo mobile com cards expansíveis.
- `Dieta.xlsx`: fonte dos dados, incluindo a coluna `Quantidades`.

## O que mudou
- Toque em uma refeição para abrir a lista de alimentos e quantidades.
- Toque novamente para fechar.
- O checkbox continua exclusivo para marcar a tarefa como concluída.
- As quantidades vêm da coluna `Quantidades` da aba `Dieta`.
- Treinos não abrem lista de alimentos.

## Publicar no GitHub Pages
Substitua no repositório os arquivos antigos `index.html` e `Dieta.xlsx` por estes novos arquivos.

A estrutura deve ficar assim:

```
/
├── index.html
└── Dieta.xlsx
```

O HTML carrega `./Dieta.xlsx`, então os dois arquivos precisam estar na mesma pasta.

## Editar as quantidades
Na aba `Dieta`, a coluna `Quantidades` usa uma linha por alimento no formato:

```
Pão|2 fatias
Queijo|30 g
Leite|250 ml
```

Ao atualizar a planilha e fazer push para o GitHub, as novas quantidades aparecem no app.
