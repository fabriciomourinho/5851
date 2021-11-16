[Arquivos Paper 5851.zip](https://github.com/fabriciomourinho/5851/files/7546536/Arquivos.Paper.5851.zip)
# IEEE Latin America Transactions - 5851
A new approach to retrofit plans for distributed energy resources to mitigate adverse impacts on bulk power systems stability

São incluídos os arquivos necessários para a realização das simulações do Artigo submetido a IEEE Latin America Transcactions "5851 - A new approach to retrofit plans for distributed energy resources to mitigate adverse impacts on bulk power systems stability". 

Todas as simulações foram realizadas utilizando o software Organon, ferramenta empregada pelo Operador Nacional do Sistema Elétrico no planejamento da operação e na operação em tempo real do Sistema Interligado Nacional. A base de dados utilizada é a base de dados oficial do Sistema Interligado Nacional, com a inclusão da modelagem da desconexão em cascata de GDs, tal como apresentada no artigo. 

A modelagem da desconexão em cascata foi realizada no arquivo .DYN. Os demais arquivos foram configurados para a execução das regiões de segurança, de acordo com as premissas e critérios definidos no paper. 

Os seguintes arquivos são necessários para a realização das simulações:

Organon.prm                // arquivo de configurações

BNT1_para_DIR03-GD5.dat    // arquivo com dados de máquinas

CASO03.pwf                 // ponto de operação inicial do fluxo de potência

FEV2021_V3_uni-GD5.dyn     // modelagem eletromecânica da rede

DEF_XGET_2Q2020.def        // definições para variações nas regiões de segurança

EVT_BIPXG_DUPLA_TUXG.evt   // contingências simuladas

SEP_BMONTE_32.SPS          // representação de sistema especial de proteção 

PLOT-FM.plv                // plotagem de saída
