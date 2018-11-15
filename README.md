# Micro1
Repositório para o trabalho final de Micro1.


# TO DO
## Relatório (prioridade 1)
* Introdução
	*	Base Teórica:
		* Origem do Sinal trifásico
		* Utilidades, vantagens
		* Motivação do projeto:
			- Sincronização da fase ao longo de uma instalação ou sistema grande.
			- Serve de ferramenta
		* Puxar sardinha para a física
			- ?????
* Materiais e Métodos
	* Explicar a Placa
	* Explicar necessidade do Antibouncing
	* Explicar necessidade do Timeout
* Discussão e Atividades
	* Estudo de Conceitos
	* Implementação
* Resultados e Discussão
* Conclusão

## Apresentação Powerpoint
* Não precisa fazer introdução
* Não precisa fazer Materiais
* Listar e mostrar imagens das partes funcionais
	* Emulador 
	* Antibouncing (funciona a simulaçõa funcional e de timing, mas não testamos na placa)
	* Cópia do sinal de entrada funciona no Quartus
	* Impossibilidade de testar no Quartus o sistema de Timeout (devido à natureza retroalimentada)
## Projeto no Quartus
* Partes que faltaram:
	* Comparador
	* Sistema de Timeout (que controla aquele H do meio do circuito, que ligamos no 1 (VCC) constante)
	* Leds do timeout
* Partes presentes
	* Emulador RST
		* 3 versões da unidade de controle
			- Versão com erro de  -2 a 0
			- Versão crrigindo o erro
			- Versão final com Antibouncing System
	* Antibouncing (pertence à unidade de controle)
	* Circuito Complementar comparador
		* Compara o valor lido anteriormente e guardado com o lido agora



_________________________________________
