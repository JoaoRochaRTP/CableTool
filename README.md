# CableTool

O CableTool é um software desenvolvido em linguagem MATLAB, e tem como objectivo assistir no uso da listagem de cabos gerada pelo software de desenho [Stardraw Design](https://www.stardraw.com/sd7) na aplicação de projectos técnicos de montagem, manutenção e renovação.

## > Instalação

Este software foi compilado para poder ser instalado e corrido através de um instalador standalone, necessitando apenas de um MATLAB Runtime que o instalador descarrega e instala automaticamente.

O instalador pode ser descarregado [aqui](https://github.com/JoaoRochaRTP/CableTool/releases).

## > Como Usar?

A interface do CableTools foi feita a pensar no utilizador, tentando ser o mais simples de usar o quanto possível.
Tem dois separadores, um por cada uma das suas funcionalidades:

### - Lista de Cabos

O separador "Lista de Cabos" permite converter uma listagem de cabos do Stardraw em algo muito mais fácil de ler, tirando a informação desnecessária.

![preview 1](https://github.com/JoaoRochaRTP/CableTool/blob/main/preview_cabos.png)

Para começar, clique em <kbd>Escolher Ficheiro</kbd> e selecione a listagem de cabos gerada pelo Stardraw.
Pouco tempo depois será desbloqueado painel das Opções onde, dependendo do projecto, o utilizador pode definir certas características da lista de cabos que pretende obter.

Por fim, clique em <kbd>Iniciar</kbd> e grave a nova listagem de cabos onde quiser, no seu computador.

### - Lista de Alterações

O separador "Lista de Alterações" permite gerar uma listagem de cabos que contém apenas os cabos para acrescentar, os cabos para tirar, e os cabos que mantém-se mas sofrem alterações *(exemplo: cabo que passa a estar ligado a uma posição diferente; equipamento que muda de posição na rack; etc.)* - separados em folhas de Excel diferentes.

![preview 2](https://github.com/JoaoRochaRTP/CableTool/blob/main/preview_alteracoes.png)

Para usar, clique nos botões <kbd>Escolher Ficheiro</kbd> e selecione a listagem de cabos (gerada pelo separador "Lista de Cabos") antiga e a nova.
Por fim, clique em <kbd>Iniciar</kbd> e grave a lista de alterações de cabos onde quiser, no seu computador.
