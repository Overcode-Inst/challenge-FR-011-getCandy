# 📋 Indíce

- [Proposta](#id01)
  - [O desafio](#id01.1)
  - [Requisitos](#id01.2)
    - [Requisitos funcionais ](#id01.2.1)
    - [Requisitos não funcionais ](#id01.2.2)
    - [Requisitos não obrigatórios](#id01.2.3)
- [Screenshots](#id02)
- [O que aprendi](#id03)
- [Mão a obra...](#id04)
- [Pré-requisitos](#id05)
- [Procedimentos de instalação](#id06)
- [Desafios similares e dicas ](#id07)
- [Autor](#id08)

# 🚀 Proposta <a name="id01"></a>

Assim como Linus Torvalds disse "Falar é fácil, me mostre o código". Nós desenvolvedores nunca vamos aprender a programar e desenvolver software sem efetivamente codar, é como tentar aprender a andar de bicicleta lendo livros e vendo vídeos.

E foi assim que essa abordagem nasceu, um roadmap baseado em projetos. A ideia em seu princípio é simples, essa é uma demanda, tente encarar como um desafio técnico e completá-lo em até 7 dias.

Ao completar, não esqueça de publicar no linkedin e adicionar #handsOnRoadmap

## :trophy: O desafio <a name="id01.1"></a>

<br />

Imagine que foi pedido a você para fazer uma aplicação para uma estande de doces que vai estar em um evento. Essa aplicação vai ficar numa tela de auto-atendimento.

E o propósito é que será para agilizar os casos comuns de venda.

<br />

## :dart: Os requisitos<a name="id01.2"></a>

### :dart: Requisitos funcionais <a name="id01.2.1"></a>

<br />

Sua aplicação deve ter:

<br />

- Ao iniciar a aplicação tem um contador de quantos doces de cada tipo estão na cesta.
- Há três tipos de doces. Que tem preços e características diferentes.
- Na tela home além do contador por tipo de doce precisa ter o preço unitário e características. Também apresentando a soma do valor de cada doce e total. Terá também o nome do cliente, que só aparece se tiver um nome indicado;
  - doce 1: Doce chocolate trufado com leite condesado e limão siciliano, R$ 2,00
  - doce 2: Doce de doce de leite com recheio de maracujá com sementes cristalizadas de maracujá, R$ 3,00
  - doce 3: Doce de bolacha com paleta italiana de (morango, limão ou laranja) e mel, R$ 4,50
- Há três botões de sendo eles para?

  - Fechar pedido, reseta os valores e abre um modal informando que o pedido foi feito e será chamado pelo nome indicado.
  - Limpar, que reseta todos dados do momento, limpando para estado inicial.
  - Começar, que abre um modal para que comece a seleção dos doces.

- O modal do processo de adicionar doces têm dois fluxos diferentes, sendo o randômico ou escolha seus doces.

  - Ao abrir o modal aparece um input com nome e dois botões permitindo o cliente escolher qual fluxo irá seguir. Só pode seguir um fluxo após adicionar um nome.

- fluxo randômico

  - Esse fluxo presa pela maior quantidade de doces,então ao clicar em randõmico é mostrado um input de quantidade de dinheiro que quer gastar, e com isso é feito a distribuição de forma que sobre menos dinheiro, mas se obtenha a maior quantidade de doces.
  - antes de sair do modal é mostrado a quantidade de cada doce e o troco.

- fluxo de escolha os seus doces.

  - É um fluxo com três steps de escolha.
  - Vai aparecer o primeiro doce que é indicado a quantidade que se deseja, depois e segundo e então o terceito. Um em cada tela, e ao escolher e clicar em próximo aparece o seguinte. Pode ser escolhido zero como opção.
  - Ao escolher os três doces é mostrado uma tela de resumo, com a quantidade de cada doce.

- Ambos os fluxos voltam para a tela principal, fechando o modal.
- Só pode fechar o pedido se tiver ao menos um doce escolhido.

### :dart: Requisitos não funcionais <a name="id01.2.2"></a>

<br />

É obrigatório a utilização de:

- ReactJs
- fazer deploy
- validação de forms da forma que achar melhor

<br />

### :pushpin: Requisitos não obrigatórios <a name="id01.2.3"></a>

<br />

Você será bem avaliado se usar:

<br />

- usar HTML semântico, como tags main, section...
- usar responsividade
- organizar e dividir bem os arquivos
- Componentizar e separar bem o que achar que deve
- Usar typeScript
- Fazer funções genéricas de avançar e retornar nos fluxos do modal
- Explicar o funcionamento da função de avançar e retornar genérica para todos casos e suas vantagens eem relação a ter uma função para cada caso do modal.
- Adicionar um evento ao finalizar um fluxo que pergunte se deseja finalizar compra, que já ative o fluxo do final se a pessoa clicar em sim, fluxo que seria ativado por botão da home. Fazendo isso com curriyng functions é algo ainda mais bem visto.
- Explicar o que é handling functions e curried functions.

<br />

# :camera_flash: Screenshots <a name="id02"></a>

<br />

## :iphone: Mobile design

## :iphone: Tablets design

## :desktop_computer: Desktop design

# :heavy_check_mark: O que aprendi <a name="id03"></a>

# 🛠 Mão a obra... <a name="id04"></a>

Você pode forkar esse projeto e reutilizar o readme e estrutura, mas também se sinta livre para mudar ela ou mesmo criar a sua.

# ☑️ Pré-requisitos para rodar <a name="id05"></a>

<br />

- [x] Editor de código de sua preferência (recomendado VS code)
- [x] Git
- [x] ?

<br />

# 📝 Procedimentos de instalação <a name="id06"></a>

<br />

Clone este repositório usando o comando:

```bash
git clone https://github.com/<meu_user>/<my-repo>.git
```

```bash
#processos adicionais aqui
```

<br />

# 👨🏾‍💻 Desafios similares e dicas <a name="id07"></a>

Antes ou depois de realizar esse desafio, você pode pegar desafios parecidos do front-end mentor ou similares. Isso te ajuda a fixar e melhorar. Vou deixar alguns a seguir, pode te ajudar a se inspirar.

O segredo aqui é fazer modelos parecidos até ganhar algum conforto com fazer algo com essas técnicas e esse modelo de desafio, então quem sabe pegar outros mais difíceis.

Você também pode usar o dribbble para se inspirar.

[Dribbble](https://dribbble.com)

# :sunglasses: Autor <a name="id08"></a>

<br />

- Linkedin - [Jean Carlos De Meira](https://www.linkedin.com/in/jeanmeira/)
- Instagram - [@jean.meira10](https://www.instagram.com/jean.meira10/)
- GitHub - [JCDMeira](https://github.com/JCDMeira)
