# Folha de Referência do Markdown

Tradução automática do ChatGPT com revisão do prof. Filipe Mendonça de Lima.
Para ver os códigos utilizados para gerar esse texto, cliquem no botão de editar para ver o código-fonte.

Obrigado por visitar o [Guia de Markdown (em inglês)](https://www.markdownguide.org)!

Esta folha de referência de Markdown fornece uma visão geral rápida de todos os elementos de sintaxe do Markdown. Ela não cobre todos os casos extremos, então, se você precisar de mais informações sobre qualquer um desses elementos, consulte os guias de referência de [Sintaxe Básica (em inglês)](https://www.markdownguide.org/basic-syntax/) e [Sintaxe Avançada (em inglês)](https://www.markdownguide.org/extended-syntax/).

## Sintaxe Básica

Estes são os elementos descritos no documento original de design de John Gruber. Todas as aplicações de Markdown suportam esses elementos.

### Títulos

# H1
## H2
### H3

### Negrito

**texto em negrito**

### Itálico

*texto em itálico*

### Citação

> citação

### Lista Ordenada

1. Primeiro item
2. Segundo item
3. Terceiro item

### Lista Não Ordenada

- Primeiro item
- Segundo item
- Terceiro item

### Código

`código`

### Linha Horizontal

---

### Link

[Guia de Markdown (em inglês)](https://www.markdownguide.org)

### Imagem

![texto alternativo](https://www.markdownguide.org/assets/images/tux.png)

## Sintaxe Avançada

Esses elementos estendem a sintaxe básica adicionando recursos adicionais. Nem todas as aplicações de Markdown suportam esses elementos.

### Tabela

| Sintaxe | Descrição |
| ----------- | ----------- |
| Cabeçalho | Título |
| Parágrafo | Texto |

### Bloco de Código Cercado

```
{
  "Nome": "João",
  "Sobrenome": "Silva",
  "idade": 25
}
```

### Nota de Rodapé

Aqui está uma frase com uma nota de rodapé. [^1]

[^1]: Esta é a nota de rodapé.

### ID de Título

### Meu Grande Título {#id-personalizado}

### Lista de Definições

termo
: definição

### Tachado

~~O mundo é plano.~~

### Lista de Tarefas

- [x] Escrever o comunicado de imprensa
- [ ] Atualizar o site
- [ ] Contatar a mídia

### Emoji

Isso é muito engraçado! :joy:

(Também veja [Copiando e Colando Emoji (em inglês)](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Destaque

Eu preciso destacar estas ==palavras muito importantes==.

### Subscrito

H~2~O

### Sobrescrito

X^2^
