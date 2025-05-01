# TCC-EMI-Conduzida-PSoC6
Este repositório tem o objetivo de armazenar os programas usados e os dados gerados durante a execução do meu Trabalho de Conclusão de Curso (TCC) "Análise dos efeitos de interferência eletromagnética conduzida no funcionamento de um conversor analógico-digital de um SoC programável." pela UFRGS sob orientação do Prof. Tiago Balen (2025).

*Programa PSoC 6 monitor:*
- Responsável por monitorar a saída serial do computador e armazenar os dados em um .txt
Nota: os arquivos aqui presentes foram modificados a partir dos originais desenvolvidos por Eduardo Fabbris

- Crie uma pasta chamada "psco6_monitor" no seu computador. 
- Copie e descompacte as pastas "build.zip", "log.zip", "temp.zip" e "others.zip" na pasta "psoc6_monitor" do seu computador.
- Retire o conteúdo da pasta "others" e cole na pasta "psoc6_monitor" e apague a pasta "others". 
- Para rodar a aplicação de monitoramente, apenas dê dois clicks no arquivo "monitor_psoc.exe"
 
*Programa embarcado no PSoC 6 PRINCIPAL:*
- Responsável por programar o circuito dentro do IC que contém o DAC ligado uma memória e um ADC ligado a uma saída serial
Nota: os arquivos aqui presentes foram modificados a partir dos originais desenvolvidos por Eduardo Fabbris e Douglas Anderson Siqueira 

- Copie e descompacte a pasta "projeto_IC.zip" para seu computador.
- Abra o projeto "projeto_IC.cywrk" no PSoC Creator e grave seu PSoC principal. 

*Programa embarcado no PSoC 6 WATCHDOG*
- Responsável pelo watchdog.
Nota: os arquivos aqui presentes são os originais desenvolvidos por Eduardo Fabbris e Douglas Anderson Siqueira

- Copie e descompacte a pasta "externalWatchDog.zip" para seu computador.
- Abra o projeto "projeto_IC.cywrk" no PSoC Creator e grave seu PSoC de watchdog.

*Dados gerados durante o TCC*
- Esta pasta contém tanto os dados "crus" quanto os gráficos e dados selecionados para o projeto.
- Copie e descompacte a pasta "data.zip" para seu computador.

*Dados Vin*
- Assim como descrito no TCC, é necessário que escrevamos no programa que irá embarcado no PSoC principal o valor que terá a tensão de entrada do ADC Vin. Nesta pasta você encontrará alguns exemplos já prontos de valores de Vin (basta copiar e colar na memória que será utilizada pelo DAC), assim como um notebook e um arquivo python com o gerador desse arquivo txt, caso seja necessário o uso de outros valores de Vin.
- Copie e descompacte a pasta "files_Vin.zip" para seu computador.

