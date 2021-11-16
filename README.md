[Arquivos Paper 5851.zip](https://github.com/fabriciomourinho/5851/files/7546536/Arquivos.Paper.5851.zip)
# IEEE Latin America Transactions - 5851
A new approach to retrofit plans for distributed energy resources to mitigate adverse impacts on bulk power systems stability

The files necessary to carry out the simulations of the paper submitted to IEEE Latin America Transcactions "5851 - A new approach to retrofit plans for distributed energy resources to mitigate adverse impacts on bulk power systems stability" are included.

All simulations were performed using the Organon software, a tool used by the Brazilian Interconnected Electric System Operator, in the operation planning and real-time operation of the Brazilian Interconnected Power System. The database used is the official database of the Brazilian Interconnected Power System, with the inclusion of the cascade disconnection modeling of DGs, as presented in the paper.

Cascading disconnect modeling was performed in the "FEV2021_V3_uni-GD5.DYN" file. The other files were configured for the execution of the DSR, according to the premises and criteria defined in the paper.

The following files are required to carry out the simulations:

organon.prm // settings file

BNT1.dat // file with machine datas

CASE03.pwf // power flow initial operating point

FEV2021_V3_uni-GD5.dyn // electromechanical modeling of the network and equipment

DEF_XGET_2Q2020.def // definitions for DSR

EVT_BIPXG_DUPLA_TUXG.evt // simulated contingencies

SEP_BMONTE_32.SPS // Special Protection System Representation

PLOT-FM.plv // output plot

Em português:

São incluídos os arquivos necessários para a realização das simulações do Artigo submetido a IEEE Latin America Transcactions "5851 - A new approach to retrofit plans for distributed energy resources to mitigate adverse impacts on bulk power systems stability". 

Todas as simulações foram realizadas utilizando o software Organon, ferramenta empregada pelo Operador Nacional do Sistema Elétrico no planejamento da operação e na operação em tempo real do Sistema Interligado Nacional. A base de dados utilizada é a base de dados oficial do Sistema Interligado Nacional, com a inclusão da modelagem da desconexão em cascata de GDs, tal como apresentada no artigo. 

A modelagem da desconexão em cascata foi realizada no arquivo .DYN. Os demais arquivos foram configurados para a execução das regiões de segurança, de acordo com as premissas e critérios definidos no paper. 

Os seguintes arquivos são necessários para a realização das simulações:

Organon.prm                // arquivo de configurações e premissas

BNT1.dat                   // arquivo com dados de máquinas

CASO03.pwf                 // ponto de operação inicial do fluxo de potência

FEV2021_V3_uni-GD5.dyn     // modelagem eletromecânica da rede e dos equipamentos

DEF_XGET_2Q2020.def        // definições para as regiões de segurança

EVT_BIPXG_DUPLA_TUXG.evt   // contingências simuladas

SEP_BMONTE_32.SPS          // representação de sistema especial de proteção 

PLOT-FM.plv                // arquvivo de plotagem de saída
