Apresente uma solução de como deve ser a criação de uma máquina virtual no Hyper-V.

Habilitar a função Hyper-V por meio de Configurações
1. Clique com o botão direito do mouse no botão Windows e selecione "Aplicativos e Recursos".
2. Selecione Programas e Recursos à direita, nas configurações relacionadas.
3. Selecione Ativar ou Desativar Recursos do Windows.
4. Selecione Hyper-V e clique em OK.

Criar uma máquina virtual com o Hyper-V
(Windows 10 Fall Creators Update)
1. Abra a Criação Rápida do Hyper-V no menu Iniciar.
2. Selecione um sistema operacional ou escolha o seu usando uma origem de instalação local.
   a. Se você quiser usar sua própria imagem para criar a máquina virtual, selecione Origem de Instalação Local .
   b. Selecione Alterar Origem de Instalação.
   c. Escolha o .iso ou .vhdx que você deseja transformar em uma nova máquina virtual.
   d. Se a imagem for uma imagem do Linux, desmarque a opção Inicialização Segura.
3. Selecione "Criar Máquina Virtual"


Demonstre de uma maneira simples porque essa prática é considerada um hipervisor do Tipo 2.

- O hipervisor tipo 2 também é chamado de hosted e é executado em um sistema operacional convencional como uma camada de software ou aplicação.
- Ele funciona abstraindo sistemas operacionais guest do sistema operacional host. Os recursos de máquina virtual são operados em um sistema operacional host, que é executado no hardware. 
- Esse tipo de hipervisor é mais adequado para usuários individuais que desejam executar vários sistemas operacionais em um computador pessoal. 
- VMware Workstation e Oracle VirtualBox são exemplos de hipervisores tipo 2.

Realize uma nova pesquisa para configuração do Servidor Físico, levando em consideração que o artigo é de 2011, qual a configuração ideal para um 
servidor suportar três máquinas virtuais dos mesmos tipos apresentados no artigo:

- O Hardware apresentado precisaria de um upgrade para a virtualização, pois conforme a necessidade conseguiria adequar o hardware para realizar 
uma boa performance segundo as funcionalidades. Precisaria também de um hardware atualizado e que se adeque ao tamanho da memória RAM e do 
disco rígido. 


____________________________________________________________________________________________________________________________________________________________________

habilitar hyper-V no Windows Server 2008
Server Manager
Clicar em Start
Administrative Toolss
Clicar em Server Manager
Add Roles
selecionar a opÃ§Ã£o Hyper-V em Roles
selecionar uma placa de rede para a rede virtual
reiniciar o servidor 
Criar a mÃ¡quina virtual de exemplo
Acessar Server Manager
Roles
Hyper-V
Hyper-V Manager
Acessar o menu Action - New - Virtual Machine - Wizard
Especificar o nome da VM
Atribuir a quantidade  de memÃ³ria RAM
selecionar o adaptador de rede virtual
conectar um disco
escolher criar um disco virtual
escolher usar um disco existente
realizar a configuraÃ§Ã£o do sistema operacional
clicar com botÃ£o direito na Vm
clicar em Settings
IDE Controller 1, selecione a imagem do Sistema Operacional
Clicar em conectar a VM
Ligar a VM
instalar o sistema operacional
hypervisor do tipo 2
Este tipo de arquitetura necessita do sistema operacional para que sejam executadas as mÃ¡quinas virtuais
Sistema operacional Ã© o host
