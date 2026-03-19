# 09. Matemática

> Vá para a [documentação](https://zensical.org/docs/authoring/math/)

$$
\cos x=\sum_{k=0}^{\infty}\frac{(-1)^k}{(2k)!}x^{2k}
$$

!!! warning "Necessita configuração"
    Note que o MathJax é incluído via uma tag `script` nesta página e não está
    configurado na configuração padrão gerada para evitar incluí-lo em
    páginas que não precisam dele. Veja a documentação para detalhes sobre como
    configurá-lo em todas as suas páginas se elas forem mais pesadas em Matemática do que estas
    páginas iniciais simples.

<script id="MathJax-script" async src="https://unpkg.com/mathjax@3/es5/tex-mml-chtml.js"></script>
<script>
  window.MathJax = {
    tex: {
      inlineMath: [["\\(", "\\)"]],
      displayMath: [["\\[", "\\]"]],
      processEscapes: true,
      processEnvironments: true
    },
    options: {
      ignoreHtmlClass: ".*|",
      processHtmlClass: "arithmatex"
    }
  };
</script>
