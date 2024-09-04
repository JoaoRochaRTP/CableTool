# CableTool

O CableTool é um software desenvolvido em linguagem MATLAB, e tem como objectivo assistir no uso da listagem de cabos gerada pelo software de desenho [Stardraw Design](https://www.stardraw.com/sd7) na aplicação de projectos técnicos de montagem, manutenção e renovação.

## > Instalação

Este software foi compilado para poder ser instalado ou corrido através de um executável standalone, necessitando apenas de um MATLAB Runtime que o executável descarrega e instala automaticamente.

O instalador pode ser encontrado nas releases, ou ao clicar [aqui](https://github.com/JoaoRochaRTP/CableTool/releases/download/v1.0/CableTool_installer_v1_0.exe).

## > Como Usar?

A interface do CableTools foi feita a pensar no utilizador, tentando ser o mais simples de usar o quanto possível.
Tem dois separadores, um por cada uma das suas funcionalidades:

### - Lista de Cabos

O separador Lista de Cabos permite converter uma listagem de cabos do Stardraw em algo muito mais fácil de ler, tirando a informação desnessária.

![teste1](https://github.com/JoaoRochaRTP/CableTool/blob/main/lista_cabos.png)

Para começar, clique em <kbd>Escolher Ficheiro</kbd> e selecione a listagem de cabos gerada pelo Stardraw.
O CableTool irá ler alguma informação básica do ficheiro, nomeadamente os tipos de cabos que constam na lista.
Pouco tempo depois será desbloqueado painel das Opções onde, dependendo do projecto, o utilizador pode definir certas características da lista de cabos que pretende obter:
. **Ordenar por número de cabo** - 
. **Ignorar cabos não identificados** - 
. **Tipos de cabos em folhas separadas** - 
. **Mostrar fabricante e modelo de equipamentos** - 
. **Gerar lista de avisos** - 
. **Separar cabos/inter-área** - 
. **Tipos de cabo** - 

Por fim, clique em <kbd>Iniciar</kbd> e grave a nova listagem de cabos onde quiser, no seu computador.

### - Lista de Alterações

O separador Lista de Alterações permite gerar uma listagem de cabos onde apareçem as diferenças 

![teste2](https://github.com/JoaoRochaRTP/CableTool/blob/main/lista_alteracoes.png)

Para usar, clique nos botões <kbd>Escolher Ficheiro</kbd> e selecione a listagem de cabos (gerada pelo separador "Lista de Cabos") antiga e a nova.
Por fim, clique em <kbd>Iniciar</kbd> e grave a listagem de alterações de cabos onde quiser, no seu computador.
