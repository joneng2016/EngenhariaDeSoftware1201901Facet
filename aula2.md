<h4> Modelos de Processo </h4>
<ul>
	<li>Modelos de Processo Prescritivo</li>
	<ul>
		<li>
			Originalmente, modelos de processo prescritivo foram propostos para trazer ordem ao caos existente na área de desenvolvimento de software.
		</li>
		<li>
			O limiar do caos é definido como “um estado natural entre ordem e caos, um grande compromisso entre estrutura e surpresa” [Kau95]. O limiar do caos pode ser visualizado como um estado instável, parcialmente estruturado... Instável porque é constantemente atraído para o caos ou para a ordem absoluta. Temos uma tendência de pensar que ordem é o estado ideal da natureza. Isso pode ser um erro.	Pesquisas... Defendem a teoria de que a operação longe do equilíbrio gera criatividade, processos auto-organizados e lucros crescentes [Roo96]. Ordem absoluta implica ausência de variabilidade, o que	poderia ser uma vantagem em ambientes imprevisíveis. A mudança ocorre quando existe uma estrutura que permita que a mudança possa ser organizada, mas tal estrutura não deve ser tão rígida a ponto de
			impedir que a mudança ocorra. Por outro lado, caos em demasia pode tornar impossível a coordenação e a coerência. A falta de estrutura nem sempre implica desordem.
		</li>
		<li>
			Se os modelos de processos prescritivos5 buscam ao máximo a estrutura e a ordem, seriam eles inapropriados para um mundo de software que prospera com as mudanças?
		</li>
		<li>
			Nas seções seguintes, examina-se a abordagem de processos prescritivos no qual a ordem e a consistência do projeto são questões dominantes
		</li>
	</ul>
	<li>O Modelo em Cascata</li>
	<ul>
		<li>	
			Há casos em que os requisitos de um problema são bem compreendidos — quando o trabalho flui da comunicação ao emprego de forma relativamente linear
		</li>
		<li>
			 Pode ocorrer também em um número limitado de novos esforços de desenvolvimento, mas apenas quando os requisitos estão bem definidos e são razoavelmente estáveis.
		</li>
		<li>
			O modelo cascata, algumas vezes chamado ciclo de vida clássico, sugere uma abordagem sequencial e sistemática6 para o desenvolvimento de software, começando com o levantamento de necessidades por parte do cliente, avançando pelas fases de planejamento, modelagem, construção, emprego e culminando no suporte contínuo do software concluído (Figura 2.3).
		</li>
		<li>
			COMUNIUCAÇÃO -> PLANEJAMENTO -> MODELAGEM -> CONSTRUÇÃO -> EMPREGO
		</li>
		<li>
			O modelo cascata é o paradigma mais antigo da engenharia de software. Entretanto, ao longo das últimas três décadas, as críticas a este modelo de processo fez com que até mesmo seus mais ardentes defensores questionassem sua eficácia [Han95]
		</li>
	</ul>
	<ul>
		<li>Modelos de Processos Incremental</li>
		<li>
			Em várias situações, os requisitos iniciais do software são razoavelmente bem definidos, entretanto, devido ao 	escopo geral do trabalho de desenvolvimento, o uso de um processo puramente linear não é utilizado. 
		</li>
		<li>
			Cada sequência linear gera “incrementais” (entregáveis/aprovados/liberados) do software [McD93] de maneira similar aos incrementais gerados por um fluxo de processos evolucionários (Seção 2.3.3).
		</li>
		<li>
			Por exemplo, um software de processamento de texto desenvolvido com o emprego do paradigma incremental, poderia liberar funções básicas de gerenciamento de arquivos, edição e produção de documentos no primeiro incremento; 
		</li>
		<li>
			recursos mais sofisticados de edição e produção de documentos no segundo; revisão ortográfica e gramatical no terceiro;
		</li>
		<li>
			E, finalmente, recursos avançados de formatação (layout) de página no quarto incremento. 
		</li>
		<li>
			O modelo de processo incremental tem seu foco voltado para a entrega de um produto operacional com cada incremento. 
		</li>
		<li>
			Os primeiros incrementos são versões seccionadas do produto final, mas eles realmente possuem capacidade para atender ao usuário e também oferecem uma plataforma para avaliação do usuário
		</li>
	</ul>
	<ul>
		<li>
			Modelos de processo evolucionário
		</li>
		<li>
			Software, assim como todos sistemas complexos, evolui ao longo do tempo
		</li>
		<li>
			Conforme o desenvolvimento do projeto avança, as necessidades de negócio e de produto mudam frequentemente, tornando inadequado seguir um planejamento em linha reta de um produto final.
		</li>
		<li>
			Um conjunto do produto essencial ou das necessidades do sistema está bem compreendido, entretanto, detalhes de extensões do produto ou do sistema ainda devem ser definidos.
		</li>
		<li>
			Modelos evolucionários são iterativos. Apresentam características que possibilitam desenvolver versões cada vez mais completas do software. Nos parágrafos seguintes, são apresentados dois modelos comuns em processos evolucionários.
		</li>
		<li>
			Frequentemente, o cliente define uma série de objetivos gerais para o software, mas não identifica, detalhadamente, os requisitos para funções e recursos.
		</li>
		<li>
			Em outros casos, o desenvolvedor encontra-se inseguro quanto à eficiência de um algoritmo, quanto à adaptabilidade de um sistema operacional ou quanto à forma em que deva ocorrer a interação homem/máquina.
		</li>
		<li>
			Em situações como essas, e em muitas outras, o paradigma de prototipação pode ser a melhor escolha de abordagem.
		</li>
		<li>
			O projeto rápido leva à construção de um protótipo, que é empregado e avaliado pelos envolvidos, que fornecerão um retorno (feedback), que servirá para aprimorar os requisitos. 
		</li>
		<li>
			Na maioria dos projetos, o primeiro sistema dificilmente é utilizável. Pode estar muito lento, muito grande, estranho em sua utilização ou as três coisas juntas. 
		</li>
		<li>
			O protótipo pode servir como “o primeiro sistema”. 
		</li>
		<li>
			 Aquele que Brooks recomenda que se jogue fora. Porém, essa pode ser uma visão idealizada. 
		</li>
		<li>
			Embora alguns protótipos sejam construídos como “descartáveis”, outros são evolucionários, no sentido de que evoluem lentamente até se transformar no sistema real.
		</li>
	</ul>
	<ul>
		<li>
			Modelo em Espeiral
		</li>
		<li>
			Usando-se o modelo espiral, o software será desenvolvido em uma série de versões evolucionárias. 
		</li>
		<li>
			Nas primeiras iterações, a versão pode consistir em um modelo ou em um protótipo. Já nas iterações posteriores, são produzidas versões cada vez mais completas do sistema que passa pelo processo de engenharia.
		</li>
		<li>
			Um modelo espiral é dividido em um conjunto de atividades metodológicas definidas pela equipe de engenharia de software. 
		</li>
		<li>
			O primeiro circuito em volta da espiral pode resultar no desenvolvimento de uma especificação de produto
		</li>
		<li>
			Passagens subsequentes em torno da espiral podem ser usadas para desenvolver um protótipo e, então, progressivamente, versões cada vez mais sofisticadas do software. 
		</li>
		<li>
			Diferente de outros modelos de processo, que terminam quando o software é entregue, o modelo espiral pode ser adaptado para ser aplicado ao longo da vida do software. 
		</li>
	</ul>
	<ul>
		<li>Modelos Concorrentes</li>
		<li>
			Possibilita à equipe de software representar elementos concorrentes e iterativos de qualquer um dos modelos de processos descritos neste capítulo
		</li>
	</ul>
</ul>