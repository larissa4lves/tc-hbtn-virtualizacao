Apresente uma solução de como deve ser a criação de uma máquina virtual no Hyper-V.

Habilitação Hyper-V

Clique com o botão direito do mouse no botão Windows e selecione "Aplicativos e Recursos". Selecione Programas e Recursos à direita, nas configurações relacionadas. Selecione Ativar ou Desativar Recursos do Windows. Selecione Hyper-V e clique em OK.

Criação da VIRTUAL MACHINE -VM

1-abrir o gerenciador de hyper-v 2 - clicar com o lado direito do mouse na maquina host 3 - novo 4- maquina virtual 5 - avançar tela 6 - especificar nome e local de armazenamento da VM / avançar 7 - especificar Geração e no caso selecionaremos a Geração 2 / avançar 8 - atribuir tamanho da memória RAM / avançar 9 - conectar disco rigido virtual escolhendo o tamanho do disco / avaçar 10 - selecionar copia ISO do SO para instalação / avançar 11- verificar resumo 12 - concluir

Demonstre de uma maneira simples porque essa prática é considerada um hipervisor do Tipo 2.

O hipervisor tipo 2 também é chamado de hosted e é executado em um sistema operacional convencional como uma camada de software ou aplicação. Ele funciona abstraindo sistemas operacionais guest do sistema operacional host. Os recursos de máquina virtual são operados em um sistema operacional host, que é executado no hardware.

Esse tipo de hipervisor é mais adequado para usuários individuais que desejam executar vários sistemas operacionais em um computador pessoal. VMware Workstation e Oracle VirtualBox são exemplos de hipervisores tipo 2.

Realize uma nova pesquisa para configuração do Servidor Físico, levando em consideração que o artigo é de 2011, qual a configuração ideal para um servidor suportar três máquinas virtuais dos mesmos tipos apresentados no artigo:

O Hardware apresentado precisaria de um upgrade para a virtualização, pois conforme a necessidade conseguiria adequar o hardware para realizar uma boa performance segundo as funcionalidades. Precisaria também de um hardware atualizado e que se adeque ao tamanho da memória RAM e do disco rígido.

________________





habilitar hyper-V no Windows Server 2008 Server Manager Clicar em Start Administrative Toolss Clicar em Server Manager Add Roles selecionar a opÃ§Ã£o Hyper-V em Roles selecionar uma placa de rede para a rede virtual reiniciar o servidor Criar a mÃ¡quina virtual de exemplo Acessar Server Manager Roles Hyper-V Hyper-V Manager Acessar o menu Action - New - Virtual Machine - Wizard Especificar o nome da VM Atribuir a quantidade de memÃ³ria RAM selecionar o adaptador de rede virtual conectar um disco escolher criar um disco virtual escolher usar um disco existente realizar a configuraÃ§Ã£o do sistema operacional clicar com botÃ£o direito na Vm clicar em Settings IDE Controller 1, selecione a imagem do Sistema Operacional Clicar em conectar a VM Ligar a VM instalar o sistema operacional hypervisor do tipo 2 Este tipo de arquitetura necessita do sistema operacional para que sejam executadas as mÃ¡quinas virtuais Sistema operacional Ã© o host
