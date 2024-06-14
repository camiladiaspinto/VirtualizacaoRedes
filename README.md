Este projeto foi desenvolvido no âmbito da unidade curricular de Gestão e Virtualização de Redes, no 1º semestre do 1º ano do Mestrado em Engenharia de Telecomunicações e Informática.O principal objetivo é introduzir Redes Definidas por Software (SDNs), focando especificamente na programação do plano de dados utilizando Processadores de Pacotes Independentes de Protocolo (P4). O P4 é uma linguagem específica para dispositivos de rede que define como estes processam pacotes.
Para adquirir proficiência nas ferramentas, configurámos o ambiente de desenvolvimento com os seguintes componentes:

    BMv2 (Behavioral Model version 2): A segunda iteração do switch de software de referência P4, utilizado para executar programas P4.
    p4c: O compilador de referência para a linguagem P4.
    Mininet: Uma ferramenta de emulação de redes open-source que permite a criação de redes virtuais num único computador.

Inicialmente, seguimos um tutorial para desenvolver um router simples. Este processo ajudou-nos a entender a arquitetura do Modelo V1, a aprender sobre os diferentes blocos e a adquirir competências de programação em P4 Seguidamente, desenvolvemos o exercício proposto: um firewall. O objetivo do firewall é restringir todo o tráfego exceto o tráfego TCP que flui de qualquer porta para a porta 5555 do h2 e da porta 5555 do h2 para qualquer porta do h1. 
