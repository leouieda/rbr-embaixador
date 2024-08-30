# Embaixadores da Rede Brasileira de Reprodutibilidade

Material de inscrição no [programa de embaixadores da Rede Brasileira de
Reprodutibilidade](https://www.reprodutibilidade.org/programa-de-embaixadores).

Documentos produzidos aqui:

- Carta de motivação: `motivacao.tex`
- Plano de atividades: `plano.tex`

## Gerando os PDFs

Baixe uma cópia deste repositório utilizando o programa `git`:

```bash
git clone git@github.com:leouieda/rbr-embaixador.git
cd rbr-embaixador
```

Os dois documentos foram escritos utilizando o LaTeX. Ambos podem ser
compilados com qualquer distribuição do LaTeX, porém recomendo utilizar o
[Tectonic](https://tectonic-typesetting.github.io/en-US/).
Caso utilize o gerenciador de pacotes `conda` ou `mamba` (comum para quem
trabalha com a linguagem Python), o Tectonic e o programa `make` podem ser
instalado com um comando no terminal a partir do arquivo `environment.yml`:

```bash
conda env create -f environment.yml
```

Os documentos PDF podem ser gerados a partir dos códigos fonte utilizando os
comandos definidos no `Makefile` rodando:

```bash
make
```

## Licença/License

The contents of this repository are licensed under a
<a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons
Attribution 4.0 International License</a>.
