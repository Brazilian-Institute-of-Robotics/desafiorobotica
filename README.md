# DESAFIO ROBÓTICA

![banner](https://github.com/Brazilian-Institute-of-Robotics/desafiorobotica/blob/master/resources/banner.PNG)

Este repositório contém os arquivos V-REP para executar a simulação do **DESAFIO** referente ao **PROGRAMA JOVENS TALENTOS - Robótica e Sistemas Autônomos** para atuação como bolsista no **SENAI CIMATEC**.

# Aviso

Certifique-se de ler e entender todas as regras do desafio disponíveis em [resources/regulamento_challenge.pdf](https://github.com/Brazilian-Institute-of-Robotics/desafiorobotica/blob/master/resources/regulamento_challenge.pdf)

# Organização

A organização das pastas é a seguinte:

- `resources` - Arquivos de suporte geral.

- `vrep_content` - Contém a cena da simulação para o desafio. Você pode carregá-lo dentro do simulador V-REP.

# Instalação

O simulador foi concebido usando o Ubuntu 16.04 e V-REP 3.6.2 (rev.0) . Outras versões de software podem funcionar, mas elas não são recomendadas pela competição.

Siga as etapas abaixo para configurar o V-REP:

**1.** Faça o download do **V-REP PRO EDU V3.6.2 rev0** no site da Coppelia Robotics: http://www.coppeliarobotics.com/downloads.html

**2.** Descompacte-lo (preferencialmente) para sua pasta **home** e renomeie a pasta como `vrep`.

**3.** Clone e faça o download deste repositório na pasta de sua `preferência`.

```
$ git clone https://github.com/Brazilian-Institute-of-Robotics/desafiorobotica.git
``` 

# Desenvolvimento

Para executar o simulador, faça o seguinte:

**1.** Abra um novo terminal e execute `$ <vrep_folder>/vrep.sh`.

**2.** Vá para File > Open Scene...e localize o cenário V-REP em `<desafiorobotica>/vrep_content/challenge_scenario.ttt`.
  
**3.** Execute o simulador indo para `Simulation > Start simulation`.

**4.** Você deve alterar o script do `Quadricopter` para realizar a **missão**.

# Dúvidas

Se você tiver dúvidas sobre o desafio, pode entrar em contato: `desafio.robotica@fieb.org.br`.

Dúvidas sobre o simulador e/ou implementação **NÃO** serão respondidas por e-mail.


**Sem esforço não há recompensa!**
