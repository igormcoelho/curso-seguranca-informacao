## Curso Segurança da Informação

Materiais gerais de Segurança da Informação do [Prof. Igor Machado Coelho](https://igormcoelho.github.io), bem como suas respectivas aplicações em períodos recentes.

![last-commit](https://img.shields.io/github/last-commit/igormcoelho/curso-seguranca-informacao)

Lista completa de módulos no repositório:

- Atualizando

Materiais PDF-HTML:

1. [Princípios Básicos](slides/1-principios/1-principios.md): [PDF](slides/1-principios/1-principios.pdf) [Online](https://igormcoelho.github.io/curso-seguranca-informacao/slides/1-principios/index.html)
   - Vídeos YouTube: [Introdução - Raphael Machado](https://www.youtube.com/watch?v=5j0PPYLbeyw) 


***Observação:*** **alguns módulos só são oferecidos para cursos específicos.*

-------

## Cursos recentes

- Segurança da Informação - TCC00341 - A1
   * [Graduação 2024.1](./slides/0-intro-curso-uff-2024-1/0-intro-curso.pdf) (mar./2024-jul./2024)
   * Instituto de Computação (IC) - Universidade Federal Fluminense (UFF)

-------

## Sobre gravações

Gravações disponibilizadas no YouTube e Classroom foram feitas com OBS (obrigado pelas dicas Mateus Nazário). Algumas dicas:

- https://medium.com/@igormcoelho/dicas-para-obs-no-linux-para-google-meet-8ac102972183

Utilizei o Okular para marcação do PDF (obrigado Matheus Nohra Haddad pelas dicas).

## Como esses slides foram feitos?

Estes slides foram feitos em `markdown` e `pandoc` (super fácil!) de acordo com o tutorial [ilectures-pandoc](https://github.com/igormcoelho/ilectures-pandoc).

Basicamente, é necessário instalar o pandoc e, opcionalmente, copiar alguns filtros úteis do tutorial (dois arquivos python). Então, é possível gerar, a partir do `markdown`, uma versão PDF LaTeX+Beamer, e outra web utilizando RevealJS. O tutorial explica tudo em detalhes.

O mais legal é que a edição do slide tem uma visualização em tempo real, com plugins disponíveis para editores populares como Atom e VSCode.
Uma demonstração foi colocada no site do ilectures: [https://github.com/igormcoelho/ilectures-pandoc#demonstrations](https://github.com/igormcoelho/ilectures-pandoc#demonstrations).


### Deps

Pandoc + LaTeX

`python3 -m pip install pandoc-source-exec`
`python3 -m pip install pandoc-latex-color`

[pandoc 2.10.1](https://github.com/jgm/pandoc/releases/tag/2.10.1)



### Licença CC-BY 4.0

Você pode: (Share) copiar e redistribuir esse material em qualquer formato; (Adapt) adaptar esse material, mesmo que para uso comercial.

Você deve: (Attribution) dar crédito apropriado, bem como um link para o original e a indicação das mudanças que você fez.

Veja licença original [CreativeCommons CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

```
curso-programacao-orientada-objetos (c) by Igor M. Coelho

curso-programacao-orientada-objetos is licensed under a
Creative Commons Attribution 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by/4.0/>.
```

Copyleft 2024
