# AULA06_03_2020.
# CSS.
## Conceito.
É uma especificação que define como os elementos que compõem uma página, um documento ou aplicação Web serão exibidos.O CSS traz toda a informação do layout, isto é, cores, posicionamento, fontes, tamanhos e imagens de fundo, enquanto o HTML deve fornecer uma “arquitetura” para o conteúdo. 
## Aplicação
Seus benefícios mais concretos são:
-Controle de interface em diferentes documentos em um único arquivo;
-Controle de diferentes interfaces para diferentes dispositivos (responsive design);
-Precisão para manter a mesma interface para diferentes navegadores;
-Melhorias na acessibilidade com a possibilidade de “esconder” elementos da tela para usuários sem problemas de visão, mas manter os mesmos elementos acessíveis para leitores de tela;  
-Formulários com look and feel diferente do padrão do sistema operacional;
-Menor consumo de banda para usuário e servidor;
-Inúmeras técnicas dinâmicas que não poderiam ser utilizadas em tabelas.

# Seletores CSS.
## Seletores com Classe.
É utilizado antes do elemento para atribuí-lo a uma determinada classe.

## Seletores com ID.
É utilizado para atribuir um ID a um elemento.
ex: <p class="chave" id="principal">.
  
## Seletores de Atributo.
É utilizado para especificar outros atributos usando colchetes.Além disso, a seleção pode ser feita case-insensitive adicionando um "i" depois do valor.
ex: [disabled]; [type='button']; [class~=key]; [lang|=es]; [title*="example" i]; a[href^="https://"]; img[src$=".png"].

## Seletores de pseudo-classes.
Pseudo-classes, juntas com pseudo-elementos, te deixa aplicar um estilo para um elemento não apenas em relação ao conteúdo da árvore do documento, mas também em relação à fatores externos como o histórico do navegador, o estado do conteúdo, ou a posição do mouse. 
ex: selector:pseudo-class {
  property: value;
  }
  
  # Referência CSS Local(na página) e externo(diretórios e web).
  ## Método 1: Arquivo Externo CSS.
Este é o método que apresenta maior versatilidade. Um arquivo externo CSS pode ser ligado a quantas páginas desejarmos, desta forma deixando a manutenção de um site muito mais fácil. Para este método, utilizamos o elemento link, da seguinte forma:

<link href="css/arquivo.css" rel="stylesheet">

A tag link é uma tag vazia, assim como br e meta. O atributo href indica o endereço do arquivo CSS (hiper-referência), nesse exemplo um arquivo chamado "arquivo.css" dentro de uma pasta "css". O atributo rel determina a relação deste "link" com a página, aqui sendo stylesheet ou folha de estilos. Se estivéssemos utilizando a sintaxe XHTML, também é necessário o atributo type com o valor text/css. 

## Método 2: Tag style.
 Com este método, aplicamos estilos apenas na página onde as regras CSS estão inseridas. Para isso, utiliza-se a tag style dentro da tag head. Exemplo:

<style>
    p {
        color: red;
    }
</style>

## Método 3: Atributo style
sse é o método que deve ser menos utilizado, por ir contra a divisão de um página em 3 camadas. Utilizando o atributo style, podemos aplicar estilos a um elemento específico. Exemplo:

<p style="color: red;">Texto</p>


# Framework's CSS mais usados.
## Bootstrap;
Bootstrap é um framework web com código-fonte aberto para desenvolvimento de componentes de interface e front-end para sites e aplicações web usando HTML, CSS e JavaScript, baseado em modelos de design para a tipografia, melhorando a experiência do usuário em um site amigável e responsivo.
## Purecss;
A biblioteca Pure foi desenvolvida pelo Yahoo!/YUI como um conjunto muito leve de módulos CSS (menos de 6k). Pure pode ser definido como uma versão extendida do Normalize mas que também inclui estilos para ítens bem comuns como grades, formulários, botões, tabelas e menus.
## Foundation;
O Foundation é uma estrutura de front-end responsiva. O Foundation fornece uma grade responsiva e componentes de interface do usuário de HTML e CSS, modelos e trechos de código, incluindo tipografia, formulários, botões, navegação e outros elementos da interface, além de funcionalidade opcional fornecida pelas extensões JavaScript.




  
  

