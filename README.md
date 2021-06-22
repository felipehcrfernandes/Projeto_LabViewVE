# Projeto_LabViewVE
Participantes: Domingos, Felipe Fernandes, Guarnieri
Breve Manual:
-Botões:
	ON/OFF: Liga e Desliga o simulador.

	Plot: Mostra o gráfico de saída após o carregamento.

	*obs: Somente aperte o "Plot" quando a luz de aviso estiver verde.
-Dados de Entrada:
	Opções de Onda (Ring): Define a forma da onda de entrada do circuito, podendo ser: Senoidal, Quadrada, Inserir Arquivo, Inserir Função. 

	Vin(t): Caso o usuário selecione a opção "Inserir Função", ele deve escrever a função desejada no campo "Vin(t)" para definir a forma de onda.
	
	Importar Arquivos: Caso o usuário selecione a opção "Inserir Arquivo", ele deve selecionar um arquivo de texto (conforme o exemplo waveform.txt disponível no repositório)
 	contendo os dados do sinal de entrada.
	
	Amplitude, Frequência, Fase: Parâmetro de entrada para as opções de onda quadrada e senoidal. Já definido
	para as outras opções a depender do arquivo inserido, ou da função inserida.

	Duty Cycle: Parâmetro utilizado na opção de Onda Quadrada.

	Número de Amostras e Taxa de Amostragem: Parâmetro necessário para todas as opções, exceto, para a inserção de arquivos
	externos.

-Dados do Sistema: 
	
	R,L,C: Parâmetros do circuito RLC.

	Vcinicial, Iinicial: Condições iniciais do circuito RLC. 

-Saída:
	
	Opções de Gráfico (Ring): Permite ao usuário selecionar o gráfico a ser mostrado dentre as opções: tensão, corrente, tensão e corrente, entrada e saída(tensão). 

	Gráfico de Saída: Mostra a resposta temporal da grandeza selecionada no ring ao lado do "Plot".

	Opções de Zoom e Análise: Menu abaixo do gráfico de saída contendo opções para dar zoom em partes do gráfico e movimentá-lo com o mouse. 

	
	
	
-Ferramentas de Aviso:
	Barra de carregamento: A barra termina de carregar quando o gráfico de saída está
	pronto para ser "plotado".

	Luz de aviso: No início do carregamento a luz fica vermelha. Ao final, ela fica verde
	indicando que o usuário pode apertar o botão "Plot" para ver o gráfico de saída.

	*obs: Para arquivos pequenos, o usuário terá a impressão de que a barra está sempre carregada,
	isso ocorre porque o carregamento é praticamente instantâneo.

  


