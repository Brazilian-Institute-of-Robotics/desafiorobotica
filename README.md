# DESAFIO de ROBÓTICA - 2021

![banner](https://github.com/Brazilian-Institute-of-Robotics/desafiorobotica/blob/webots-2021/resources/banner.png)

Este repositório contém os arquivos necessários para a realização da simulação do **DESAFIO** referente ao **Laboratório de Robótica e Sistemas Autônomos** para atuação como estagiário de graduação no **SENAI CIMATEC**.

# Organização

A organização das pastas é a seguinte:

- `resources` - Arquivos de suporte geral.

- `webots_content` - Contém o **mundo** e o **controle** para a simulação do desafio. Você pode carregá-los dentro do simulador Webots.

# Instalação

O simulador escolhido para este desafio é o Webots <https://cyberbotics.com/#cyberbotics>.

Webots é multiplataforma, ou seja pode ser instalado em qualquer sistema operacional.

Faça o download em <https://github.com/cyberbotics/webots/releases/tag/R2021a>, escolhendo o seu sistema operacional.

Para fazer o download deste repositório basta clonar numa pasta de sua `preferência`.

```
$ git clone https://github.com/Brazilian-Institute-of-Robotics/desafiorobotica.git
``` 

# Desenvolvimento

O simulador é bem intuitivo, porém o candidato deve investir tempo para realizar alguns tutoriais disponíveis neste endereço >>> <https://cyberbotics.com/doc/guide/tutorials?tab-language=c#tutorials>.

O robô a ser utilizado é o Pioneer 3-DX <https://cyberbotics.com/doc/guide/pioneer-3dx?tab-language=c#adepts-pioneer-3-dx>.

Para executar o desafio, faça o seguinte:

**1.** Abra o Webots.

**2.** Com o Webots aberto, abra o mundo para este desafio, o mesmo está localizado em <https://github.com/Brazilian-Institute-of-Robotics/desafiorobotica/blob/webots-2021/webots_content/pioneer3dx_desafio.wbt>.
  
**3.** Para que o robô chegue até a região da, o mesmo deve fazer uso de um controle. O controle as ser utilizado está em <https://github.com/Brazilian-Institute-of-Robotics/desafiorobotica/blob/webots-2021/webots_content/desafio.c>. Veja que o controle não está otimizado para a realização da missão.

**4.** Você deve alterar o script do controle `desafio` para realizar a **missão**. Não esqueça: para alterar você precisa saber o que fazer, por isso faça os tutoriais.


# Aviso

**Certifique-se de ler e entender todas as regras do desafio disponíveis em** <https://github.com/Brazilian-Institute-of-Robotics/desafiorobotica/blob/webots-2021/resources/pioneer3dx_desafio_regras.pdf>


# Dúvidas

Se você tiver dúvidas sobre o desafio, pode entrar em contato: `marcoreis@fieb.org.br`.

Dúvidas sobre o simulador e/ou implementação **NÃO** serão respondidas por e-mail.


**Sem esforço não há recompensa!**

'This is the way.'
