![Ilum Escola de Ciência, CNPEM](https://pages.cnpem.br/workshopbioimagens/wp-content/uploads/sites/166/2023/06/logo-ilum.png)


<h1 align="center">Calculador de Bras e Kets $|\psi\rangle$</h1>

**Nome:** Bruno Bini Camargo  | **Turma:** T26 <br>
**Instituição:** Ilum Escola de Ciência, CNPEM, Campinas

Repositório para armazenar meu projeto final da disciplina de Práticas em Ciência de Dados (PCD), do 1° semestre do curso de Ciência e Tecnologia na Ilum.

## 🚀 Sobre o projeto:

O objetivo deste projeto é automatizar operações utilizando bras e kets (notação de Dirac), fundamentais em cálculos de mecânica quântica e de computação quântica. 

### O que são Bras e Kets?

Na notação do físico Paul Dirac (conhecida como notação bra-ket), bras e kets são vetores do espaço de Hilbert ($\mathbb{C}$) representados matricialmente.

Ket é um vetor representado em uma matriz coluna; já bra é um ket transposto e conjugado, sendo representado por uma matriz linha.

A operação de transposição e conjugação de um ket para a formação de um bra é conhecida como adaga ($\dagger$).

<div align="center">
  <img src="https://substackcdn.com/image/fetch/$s_!JYTy!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fd2eaa5c0-dcef-45c9-8967-8a02ed40e9ce_835x471.png" width="600" alt="Bras e kets representados matricialmente">
</div>

Nesse programa, o ket será representado como uma lista com cada elemento sendo uma outra lista: 

<h5 style="text-align: center;">$[{\,}[a],{\,} [b],{\,} [c]{\,}]$</h5>

O bra será representado como uma lista com uma sublista interna contendo os elementos (matriz linha):

<h5 style="text-align: center;">$[{\,}[a,{\,} b,{\,} c]{\,}]$</h5>

### 🧮 Operações:

Esse projeto é capaz de executar dez operações:
* **Soma de dois kets $|\psi\rangle + |\phi\rangle$**
* **Produto de um ket por escalar $\lambda |\psi\rangle$**
* **Conversão de ket em bra ($$|\psi\rangle)^\dagger = \langle\psi\vert$$:** operação adaga em um ket.
* **Produto interno $\langle\phi|\psi\rangle$:** multiplicação componente a componente de um bra por um ket, resultando em um escalar.
* **Módulo de um ket $\sqrt{\langle\psi|\psi\rangle}$:** raiz quadrada do produto interno de um ket por ele mesmo.
* **Ket normalizado $\frac{|\psi\rangle}{\sqrt{\langle\psi|\psi\rangle}}$:** divisão de cada componente do ket pelo módulo, resultando em um ket de módulo 1. 
* **Produto externo $|\psi\rangle\langle\phi|$:** multiplicação de um ket por um bra, resultando em uma matriz.
* **Aplicação de um operador em um ket $\mathit {Â}|\phi\rangle$:** multiplicação de uma matriz (operador) por um ket.
* **Elemento de matriz $\langle\psi|\mathit {Â}|\phi\rangle$:** operação que posiciona um operador Â entre um bra e um ket, resultando em um escalar.
* **Valor esperado $\langle\psi|\mathit {Â}|\psi\rangle$:** caso particular de elemento de matriz calculado utilizando o mesmo ket em ambos os lados da operação.

## :open_file_folder: Arquivos do repositório:

* :page_facing_up: **.gitignore**: Contém informações para ignorar arquivos desnecessários no Git
* :memo: **Bras e Kets.ipynb**: Contém o notebook Jupyter do projeto.
* :balance_scale: **LICENSE**: Contém informações da licença desse projeto, a GNU General Public License v2.0.
* :book: **README.md**: Contém a documentação principal do projeto

## 🖥️ Ferramentas usadas no projeto:

-
-


## Agradecimentos:
Um agradecimento especial aos professores que tornaram esse projeto possível:

Aos três professores responsáveis pela disciplina de PCD:
- Prof. Dr. Daniel Roberto Cassar
- Prof. Dr. Leandro Nascimento Lemos
- Prof. Dr. James Moraes de Almeida
  
Por me guiarem nos meus primeiros passos da programação.
 
Ao Prof. Dr. Felipe David Crasto de Lima, por me transmitir os conceitos teóricos da notação de Dirac, que são a base do programa.
