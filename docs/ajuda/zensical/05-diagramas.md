# 05. Diagramas

> Vá para a [documentação](https://zensical.org/docs/authoring/diagrams/)

``` mermaid
graph LR
  A[Início] --> B{Erro?};
  B -->|Sim| C[Hmm...];
  C --> D[Depurar];
  D --> B;
  B ---->|Não| E[Eba!];
```
