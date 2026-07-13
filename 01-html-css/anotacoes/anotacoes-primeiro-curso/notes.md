# Anotações de HTML - Estrutura Inicial

## Estrutura básica com Emmet

Usando `!` no VS Code, o Emmet gera automaticamente a estrutura inicial do HTML. Lembre-se de mudar o `lang` para `"pt-br"`.

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

---

## Tags básicas

| Tag | Função | Exemplo |
|-----|--------|---------|
| `<h1>` | Título nível 1 (mais importante) | `<h1>Título Principal</h1>` |
| `<h2>` | Título nível 2 | `<h2>Subtítulo</h2>` |
| `<h3>` | Título nível 3 | `<h3>Seção</h3>` |
| `<h4>` | Título nível 4 | `<h4>Subseção</h4>` |
| `<h5>` | Título nível 5 | |
| `<h6>` | Título nível 6 (menos importante) | |
| `<hr>` | Linha horizontal | `<hr>` |
| `<p>` | Parágrafo | `<p>Texto aqui</p>` |
| `<br>` | Quebra de linha | `<br>` |

### Hierarquia de títulos

Os títulos devem seguir uma ordem lógica:

```
h1 → h2 → h3 → h4 → h5 → h6
```

Evite pular níveis (ex.: ir direto de `<h2>` para `<h4>`).

---

## Texto de preenchimento (Lorem Ipsum)

Dentro de um `<p>`, digite `lorem` e pressione `Tab` para gerar um texto aleatório:

```html
<p>lorem</p> <!-- Gera um parágrafo com texto falso -->
```

É útil para testes durante o desenvolvimento.

---

## Emojis

### Método com código hexadecimal

```html
<p>&#x1F600;  <!-- 😀 -->
<p>&#x2764;   <!-- ❤ -->
<p>&#x1F680;  <!-- 🚀 -->
```

- Começa com `&#x` e termina com `;`
- Site com os códigos: [https://emojipedia.org/](https://emojipedia.org/)

### Método direto (mais prático)

```html
<p>Olá! 😀❤🚀</p>
```

Hoje em dia funciona direto, sem precisar de código.

---

## Sites úteis

### Imagens gratuitas

- [Unsplash](https://unsplash.com/pt-br)
- [Pexels](https://www.pexels.com/pt-br/)

> Ambos permitem uso gratuito, inclusive em projetos comerciais.

### Ícones

- [IconArchive](https://www.iconarchive.com/)

### Converter PNG para ICO (favicon)

- [Favicon.io](https://favicon.io/favicon-converter/)

---

## Outros atalhos do Emmet

| Atalho | Resultado |
|--------|-----------|
| `!` | Estrutura inicial do HTML |
| `lorem` | Texto aleatório |
| `img` | `<img src="" alt="">` |
| `a` | `<a href=""></a>` |
| `ul>li*5` | Lista com 5 itens |
| `ol>li*3` | Lista ordenada com 3 itens |
| `div.container` | `<div class="container"></div>` |

---

## Tags que serão úteis em breve

| Tag | Função |
|-----|--------|
| `<a>` | Links |
| `<img>` | Imagens |
| `<ul>` / `<ol>` / `<li>` | Listas (não ordenada / ordenada / item) |
| `<div>` | Container genérico (bloco) |
| `<span>` | Container genérico (inline) |
| `<strong>` | Texto em **negrito** |
| `<em>` | Texto em *itálico* |

---

## Dica: Word Wrap no VS Code

- **Atalho rápido:** `Alt + Z`
- **Menu:** View → Word Wrap
- **Configuração permanente:** buscar por `"word wrap"` nas settings e definir como `"on"`

---

> Anotações criadas durante os estudos de HTML. 🚀
