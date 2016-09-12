# modelo_tese_ufpr
Alteração do modelo latex v0.9.4 [disponibilizado](http://web.inf.ufpr.br/pos/alunos) pela UFPR.

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
\cite{Chave}       % --> Autor et alii (Ano)
\citep{Chave}      % --> [Autor et alii, Ano]
\citeauthor{Chave} % --> Autor et alii
\citeyear{Chave}   % --> Ano

```
