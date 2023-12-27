# O que é Bootstrap?

* É um framework CSS.
* Traz estilos CSS prontos.
* O bootstrap permite que estilizações CSS possam ser implementadas como classes HTML.

## Exemplos

### Botão em CSS:

``` css
.botao {
  border: none;
  color: white;
  background-color: #FFFF;
  padding: 7px 12px;
  border-radius: 5px;
  cursor: pointer;
  align-self: center;
}

.botao:hover {
  background-color: #1b1b1b
}
```

### Botão em Bootstrap:

``` less
<button type="button" class="btn btn-primary">Botão</button>
```

* É constituído pela linguagem [`less`](https://lesscss.org), que extende orientações em CSS para classes em HTML.
* Há também o `less.js`, que é uma ferramenta Javasctipt que converte algoritmos em javascript para estilizações em CSS.

---
