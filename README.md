# modelo_tese_ufpr
Alteração do modelo latex v0.9.4 [disponibilizado](http://web.inf.ufpr.br/pos/modelotese0.9.4.tgz) pela UFPR.

A alteração inclui o uso da biblioteca `natbib`, comportando novos estilos de citações:

```latex
% Um autor
\cite{Chave}       % --> Autor (Ano)
\citep{Chave}      % --> [Autor, Ano]
\citeauthor{Chave} % --> Autor
\citeyear{Chave}   % --> Ano

% Dois autores
\cite{Chave}       % --> Autor1 e Autor2 (Ano)
\citep{Chave}      % --> [Autor1 e Autor2, Ano]
\citeauthor{Chave} % --> Autor1 e Autor2
\citeyear{Chave}   % --> Ano

% Mais de dois autores
\cite{Chave}       % --> Autor et al. (Ano)
\citep{Chave}      % --> [Autor et al., Ano]
\citeauthor{Chave} % --> Autor et al.
\citeyear{Chave}   % --> Ano

```
