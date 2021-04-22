#Guia de Estilo

## Histórico de Versões

| Data       | Versão | Descrição                                                                                  | Autores          | Revisor          |
| ---------- | ------ | ------------------------------------------------------------------------------------------ | ---------------- | ---------------- |
| 23/03/2021 | 0.1    | Criação do Documento                                                                       | Eduarda Servidio | Pedro Haick |
| 23/03/2021 | 0.2    | Adição do tópico e subtópicos referentes a Introdução                                      | Eduarda Servidio | Giovana Dionisio |
| 23/03/2021 | 0.3    | Adição do tópico e subtópico referentes a Resultados de Análise                            | Eduarda Servidio | Giovana Dionisio |
| 24/03/2021 | 0.4    | Adição dos tópicos e subtópicos referentes a Elementos de Interface e Estilos de Interação | Hérya Rodrigues  | Eduarda Servidio |
| 24/03/2021 | 0.5    | Adição dos tópicos 5 e 6                                                                   | Luis Marques     | Eduarda Servidio |

##1. Introdução

<p align="justify">Guia de Estilo trata-se de um registro das principais decisões de design tomadas,
de forma que elas não se percam, isto é, sejam efetivamente incorporadas no produto
final.</p>
A imagem abaixo mostra a fase do Ciclo de Mayhew que estamos desenvolvendo:
<img alt= "Ciclo de Mayhew com ênfase em Guia de Estilo" src="../Images_Guia_Estilo/Esquema_Mayhew_1.jpg" width = "600"/>

_Figura1: Análise de Requisitos do Ciclo de Mayhew. Modificado por: Eduarda Servidio. Fonte: BARBOSA, Simone et al. "Interação Humano-Computador". Capítulo 6, p 88._

###1.1 Objetivo do Guia de Estilo

<p align="justify">Guias de Estilo servem de ferramenta de comunicação entre os membros da equipe
de design e também com a equipe de desenvolvimento. É importante que as decisões de
design possam ser facilmente consultadas e reutilizadas nas discussões sobre extensões
ou versões futuras do produto.</p>
<p align="justify"> A partir disso, criaremos um Guia de Estilo com a função de registrar as
decisões de design relacionadas a implementação do site CIL2-BSB.</p>

###1.2 Organização e conteúdo do Guia de Estilo

<p align="justify">O Guia de Estilo será baseado na estrutura proposta por Marcus (1991) e Mayhew (1999).</p>
Segue a estrutura detalhada:
####1) Introdução:
    * Objetivo do guia de estilo;
    * Organização e conteúdo do guia de estilo;
    * Público-alvo do guia de estilos
    * Como utilizar o guia
    * Como manter o guia
####2) Resultados de análise
	* Descrição do ambiente de trabalho do usuário
####3) Elementos de interface
	* Disposição espacial e grid
	* Janelas
	* Tipografia
	* Símbolos não tipográficos
    * Cores
    * Animações
####4) Elementos de interação
	* Estilos de interação
    * Seleção de um estilo
    * Aceleradores
####5) Elementos de ação
    * Preenchimento de campos
    * Seleção
    * Ativação
####6) Vocabulário e padrões
    * Terminologia
    * Tipos de tela
    * Sequências de diálogos

###1.3 Público-alvo do Guia de Estilos

<p align="justify">O público-alvo são os desenvolvedores e programadores do site,
assim como, a equipe que irá lidar com o design do site CIL2-BSB.</p>

###1.4 Como utilizar o Guia

<p align="justify">O Guia de Estilo deve ser utilizado como parte de um processo
reflexivo de design, e não como um conjunto de soluções prontas ou fórmulas geradoras
de soluções. O Guia deve auxiliar nas correções e melhorias do design do site do CIL2-BSB.</p>

###1.5 Como manter o Guia

<p align="justify">O Guia de Estilo deve ser feito na fase de "Análise de Requisitos" e
verificado a cada nível na fase de "Design, Avaliação, Desenvolvimento" como
indicado na imagem abaixo do Ciclo de Mayhew. O Guia deve ser mantido sempre atualizado
após cada alteração no desenvolvimento do projeto.</p>

<img alt = "Ciclo de Mayhew com ênfase em Guia de Estilo" src="../Images_Guia_Estilo/Esquema_Mayhew.jpg" width = "600"/>

_Figura2: Ciclo de Mayhew. Modificado por: Eduarda Servidio. Fonte: BARBOSA, Simone et al. "Interação Humano-Computador". Capítulo 6, p 88._

##2. Resultados de Análise

###2.1 Descrição do ambiente de trabalho do usuário

<p align="justify">O site do CIL2-BSB é um ambiente na web voltado a apresentar notícias
e orientar as pessoas, interessadas em aprender uma nova língua em Brasília, no seu
processo de matrícula.
Na tela Home do site o usuário encontra 6 Abas superiores com informações diversas sobre
tudo que diz respeito ao CIL2-BSB e seus alunos, bem como um link que redireciona ao
Facebook do Centro Interescolar. Ao longo da página Home, há uma seção de Notícias,
uma de Fotos e uma de Destaque, bem como um pequeno atalho das principais funções do site no canto
inferior direito da tela, seção Mais.</p>

Segue imagem do site do CIL2-BSB, bem como detalhamento da Aba Superior da página Home:

<img alt = "Site CIL2BSB" src="../Images_Guia_Estilo/Site_CIL2.jpg" width = "600"/>

_Figura3: Site do Cil2-BSB. Disponível em: http://www.cil2bsb.com.br/_

<img alt = "Aba Superior do Site CIL2BSB" src="../Images_Guia_Estilo/Aba_Superior.jpg" width = "600"/>

_Figura4: Aba Superior do site do Cil2-BSB. Disponível em: http://www.cil2bsb.com.br/_

## 3. Elementos de interface

### 3.1 Disposição espacial e grid

<p align="justify"> A disposição espacial atual do site é simples, mas a forma como o grid está disposto faz com que alguns elementos se confundam ou se sobreponham.
Na figura 3 do subtópico acima  - "Descrição do ambiente de trabalho do usuário" -  pode-se observar que títulos de diferentes notícias estão sobrepostos e que algumas notícias chegam a se repetir até três vezes na página inicial, mas em diferentes partes do grid.</p>

Segue abaixo o grid atual para a página inicial e diferentes janelas:

<img alt = "Grid página inicial" src="../Images_Guia_Estilo/grid-homepage.jpg" width = "600"/>

_Figura 5: Grid da página inicial_

<img alt = "Grid Notícias" src="../Images_Guia_Estilo/grid-noticias.png" width = "600"/>

_Figura 6: Grid da janela de notícias_

<img alt = "Grid das demais janelas" src="../Images_Guia_Estilo/grid-janelas.png" width = "600"/>

_Figura 7: Grid das demais janelas_

### 3.2 Janelas

<p align="justify">Além da página inicial, há 16 janelas funcionais: CIL2, Equipe Gestora, Conselho Escolar, Secretaria do CIL 02 de Brasília, APAAM, Avaliação, Regimento Interno – CIL 2, Deveres do Aluno, Matrículas Novas, Renovação de Matrícula, Trancamento de Matrícula, Notícias, Banco do Livro, Cine Cil, Monitoria e Reforço Escolar e Fale Conosco. A funcionalidade comum a todas é a visualização de informações e notícias.</p>
<p align="justify">No entanto, o menu principal - localizado na parte superior do site - redireciona o usuário a algumas janelas vazias, como a janela de Professores (Figura 8) e a do DELE (Figura 9).</p>

<img alt = "Janela Professores" src="../Images_Guia_Estilo/professores.png" width = "600"/>

_Figura 8: Janela "Professores" sem informações. Disponível em: http://www.cil2bsb.com.br/quem-somos/professores/_

<img alt = "Janela DELE" src="../Images_Guia_Estilo/DELE.png" width = "600"/>

_Figura 9: Janela "DELE" sem informações. Disponível em: http://www.cil2bsb.com.br/dele/_

### 3.3 Tipografia

As principais fontes utilizadas são Arial, Helvetica e Tahoma.
<img alt = "Fonte Arial" src="../Images_Guia_Estilo/fonteArial.png" width = "600"/>

_Figura 10: Exemplos de utilização da fonte Arial_

<img alt = "Fonte Helvetica" src="../Images_Guia_Estilo/fonteHelvetica.png" width = "600"/>

_Figura 11: Exemplos de utilização da fonte Helvetica_

<img alt = "Fonte Tahoma" src="../Images_Guia_Estilo/fonteTahoma.png" width = "600"/>

_Figura 12: Exemplos de utilização da fonte Tahoma_

### 3.4 Símbolos não tipográficos

<p align="justify">O site apresenta os seguintes símbolos não tipográficos:</p>

<img alt = "Símbolos não tipográficos" src="../Images_Guia_Estilo/nao-tipograficos.png" />

_Figura 13: Símbolos não tipográficos encontrados no site do CIL2BSB_

### 3.5 Cores

#### 3.5.1 Cores do logo

<img alt = "Cores do logo" src="../Images_Guia_Estilo/cores-logo.jpeg" />

_Figura 14: Cores do logo do CIL2BSB_

#### 3.5.2 Cores principais

<img alt = "Cores principais" src="../Images_Guia_Estilo/cores-principais.jpeg" />

_Figura 15: Principais cores encontradas no site do CIL2BSB_

#### 3.5.1 Cores secundárias

<img alt = "Cores secundárias" src="../Images_Guia_Estilo/cores-secundarias.jpeg" />

_Figura 16: Cores secundárias encontradas no site do CIL2BSB_

### 3.6 Animações

<p align="justify">O site do CIL2BSB apresenta uma animação, na Página Home na seção das Notícias, das principais e atuais notícias presentes no site.</p>

## 4.Elementos de interação

### 4.1 Estilos de interação

<p align="justify">No site do CIL2BSB é encontrado o WIMP(Windows, Icons, Menus, and Pointers), que consiste na utilização de janelas, ícones, menus e ações com o mouse. Dentre estes, o menu é o mais utilizado, de forma a possibilitar a navegação do usuário.</p>

### 4.2 Seleção de um Estilo

<p align="justify">O estilo predominante no site é o de menus. Diante disso, o usuário procura o que deseja no menu e tenta realizar a funcionalidade.</p>

### 4.3 Aceleradores (teclas de atalho)

Durante a utilização do site, não foram encontrados aceleradores de nenhum tipo.

## 5. Elementos de ação

### 5.1 Preenchimento de campos

<p aling="justify">O sistema não possui campos a serem preenchidos.</p>
 
### 5.2 Seleção
 
<p aling="justify">O usuário pode selecionar qualquer texto ou elemento no site.</p>
 
### 5.3 Ativação
 
<p aling="justify">O sistema não possui ações que necessitem de ativação por parte do usuário.</p>
 
## 6. Vocabulário e padrões
 
### 6.1 Terminologia
 
<p aling="justify">O site não usa terminologias específicas.</p>
 
### 6.2 Tipos de tela
 
<p aling="justify">O site em todas as telas fazem uso de uma barra superior (top bar) e uma barra inferior (footer).</p>

<img alt = "Cores secundárias" src="../Images_Guia_Estilo/cil2_head.png" width = "600"/>

_Figura 17: top bar site do CIL2BSB. Disponível em: http://www.cil2bsb.com.br_

<img alt = "Cores secundárias" src="../Images_Guia_Estilo/cil2_rod.png" width = "600"/>

_Figura 18: footer site do CIL2BSB. Disponível em: http://www.cil2bsb.com.br_

### 6.3 Sequências de diálogos

<p aling="justify">O site não usa sequências de diálogos, sendo as informações transmitidas sempre unilateralmente(do site para o usuário).</p>

## Bibliografia

<p align="justify">Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)
Interação Humano-Computador e Experiência do usuário. Autopublicação.
</p>
Os diagramas do tópicos Elementos de Interface e Estilos de Interação são de elaboração própria e foram criadas utilizando <a href="https://app.diagrams.net/" target="_top">draw.io</a> e <a href="https://color.adobe.com/" target="_top">Adobe Color</a>.
