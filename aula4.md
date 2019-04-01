<h5>Conceitos Gerais para Realizar o Levantamento de Requisitos</h5>
<ul>
	<li>Escopo da Engenharia de Requisitos</li>
	<li>
		As reuniões são conduzidas por e com a participação tanto dos engenheiros de software quanto de outros interessados.
	</li>
	<li>
		São estabelecidas regras para preparação e participação.
	</li>
	<li>
		É sugerida uma agenda suficientemente formal para cobrir todos os pontos importantes, porém, suficientemente informal para encorajar o fluxo livre de ideias.
	</li>
	<li>
		Um “facilitador” (pode ser um cliente, um desenvolvedor ou uma pessoa de fora) dirige a reunião.
	</li>
	<li>
		É utilizado um “mecanismo de definições” (que pode ser planilhas, flip charts, adesivos de parede ou um boletim eletrônico, salas de bate-papo ou fóruns virtuais)
	</li>
</ul>

<h5>
	Tipos de Requisitos
</h5>
<ul>
	<li>
		Requisitos normais. Refletem os objetivos e metas estabelecidos para um produto ou sistema durante reuniões com o cliente. Se esses requisitos estiverem presentes, o cliente fica satisfeito. Exemplos de requisitos normais poderiam ser tipos de displays gráficos solicitados, funções de sistema específicas e níveis de desempenho definidos.
	</li>
	<li>
		Requisitos esperados. Esses requisitos estão implícitos no produto ou sistema e podem ser tão fundamentais que o cliente não os declara explicitamente. Sua ausência será causa de grande insatisfação. Exemplos de requisitos esperados são: facilidade na interação homem–máquina, confiabilidade e correção operacional global e facilidade na instalação do software.
	</li>
	<li>
		Requisitos fascinantes. Esses recursos vão além da expectativa dos clientes e demonstram ser muito satisfatórios quando presentes. Por exemplo, o software para um novo celular vem com recursos-padrão, mas junto vem um conjunto de capacidades não esperadas (por exemplo, tecla multitoque, correio de voz visual) que deleitam todos os usuários do produto.
	</li>
</ul>

<h5>
	Cenários de Uso
</h5>
<ul>
	<li>
		Entretanto, é difícil progredir para atividades de engenharia de software mais técnicas até que entendamos como tais funções e características serão usadas por diferentes classes de usuários.
	</li>
	<li>
		Os cenários, normalmente chamados casos de uso [Jac92], fornecem uma descrição de como o sistema será utilizado. Casos de uso são discutidos de forma mais detalhada na Seção 5.4
	</li>
</ul>
<h5>
	Declarações
</h5>
<ul>
	<li>
		Uma declaração da necessidade e viabilidade.
	</li>
	<li>
		Uma declaração restrita do escopo para o sistema ou produto.
	</li>
	<li>
		Uma lista de clientes, usuários e outros interessados que participaram do levantamento de requisitos.
	</li>
	<li>
		Uma descrição do ambiente técnico do sistema.
	</li>
	<li>
		Uma lista de requisitos (preferencialmente organizada por função) e as restrições de domínio que se aplicam a cada uma delas.
	</li>
	<li>
		Um conjunto de cenários de uso que esclarecem o uso do sistema ou produto sob diferentes condições operacionais.
	</li>
	<li>
		Quaisquer protótipos desenvolvidos para melhor definição dos requisitos
	</li>
</ul>
<h5>
	Caso de Uso
</h5>
<ul>
	<li>
		Atores são as diferentes pessoas (ou dispositivos) que usam o sistema ou produto no contexto da função e comportamento a ser descritos.
	</li>
	<li>
		O usuário típico poderia desempenhar uma série de papéis diferentes ao usar um sistema, ao passo que o ator representa uma classe de entidades externas (normalmente, mas não sempre, pessoas) que desempenham apenas um papel no contexto do caso de uso.
	</li>
	<li>
		Pelo fato de o levantamento de requisitos ser uma atividade evolucionária, nem todos os atores são identificados durante a primeira iteração.
	</li>
	<li>
		Uma vez que os atores tenham sido identificados, os casos de uso podem ser desenvolvidos. Jacobson [Jac92] sugere uma série de perguntas 12 que devem ser respondidas por um caso de uso:
	</li>
	<ul>
		<li>Quem é(são) o(s) ator(es) primário(s) e o(s) ator(es) secundário(s)?</li>
		<li>Quais são as metas do ator?</li>
		<li>Que precondições devem existir antes de uma história começar?</li>
		<li>Que tarefas ou funções principais são realizadas pelo ator?</li>
		<li>Que exceções deveriam ser consideradas à medida que uma história é descrita?</li>
		<li>Quais são as variações possíveis na interação do ator?</li>
		<li>Que informações de sistema o ator adquire, produz ou modifica?</li>
		<li>O ator terá de informar o sistema sobre mudanças no ambiente externo?</li>
		<li>Que informações o ator deseja do sistema?</li>
		<li>O ator gostaria de ser informado sobre mudanças inesperadas?</li>
	</ul>
</ul>

Precondições: O sistema foi programado para uma senha e para reconhecer
vários sensores.
Disparador: O proprietário decide “acionar” o sistema, isto é, ativar as funções
de alarme.
Cenário:
1. Proprietário: observa o painel de controle
2. Proprietário: introduz a senha
3. Proprietário: seleciona “em casa” ou “fora de casa”
4. Proprietário: observa a luz de alarme vermelha para indicar que o CasaSegura foi armado
Exceções:
1. O painel de controle encontra-se no estado não disponível: o proprietário verifica todos os sensores
para determinar quais estão abertos; fechando-os.
2. A senha incorreta (o painel de controle emite um bipe): o proprietário introduz novamente a senha,
desta vez correta.
3. Senha não reconhecida: o subsistema de monitoramento e resposta deve ser contatado para repro-
gramar a senha.
4. É selecionado em casa: o painel de controle emite dois bipes e uma luz de em casa é acesa; os sen-
sores periféricos são ativados.
5. É selecionado fora de casa: o painel de controle emite três bipes e uma luz fora de casa é acesa;
todos os sensores são ativados.
Prioridade: Essencial, deve ser implementada
Quando disponível: Primeiro incremento
Frequência de uso: Várias vezes por dia
Canal com o ator: Via interface do painel de controle
Atores secundários: Técnico de suporte, sensores
Canais com os atores secundários:
Técnico de suporte: linha telefônica
Sensores: interfaces hardwired e de radiofrequência

<img src="/fig.png">

5.1. Por que um número muito grande de desenvolvedores de software não dedica mui-
ta atenção à engenharia de requisitos? Existiria alguma circunstância em que poderíamos
deixá-la de lado?
5.2. Foi lhe dada a responsabilidade de extrair os requisitos de um cliente que lhe diz que
está muito ocupado para poder atendê-lo. O que você deveria fazer?
5.3. Discuta alguns dos problemas que ocorrem quando os requisitos têm de ser obtidos de
três ou quatro clientes diferentes.
5.4. Por que dizemos que o modelo de análise representa uma reprodução de um sistema em
determinado momento?
5.5. Suponhamos que você tenha convencido o cliente (você é um excelente vendedor) a
concordar com todas as suas exigências como desenvolvedor. Isso o torna um mestre da
negociação? Por quê?
5.6. Desenvolva pelo menos três “perguntas livres de contexto” que você faria a um interes-
sado durante a atividade de concepção.
5.7. Desenvolva um “kit” de levantamento de requisitos. O kit deve incluir um conjunto de
diretrizes para realizar uma reunião para levantamento de requisitos e materiais que podem
ser utilizados para facilitar a criação de listas e quaisquer outros itens que poderiam ajudar
na definição dos requisitos.
5.8. Seu professor irá dividir a classe em grupos de quatro a seis alunos. Metade do grupo irá
desempenhar o papel do departamento de marketing e a outra fará o papel da engenharia de
software. Sua tarefa é definir os requisitos para a função de segurança do CasaSegura descri-
ta neste capítulo. Realize uma reunião para levantamento de requisitos usando as diretrizes
apresentadas neste capítulo.
5.9. Desenvolva um caso de uso completo para uma das atividades a seguir:
a. Fazer um saque em um caixa eletrônico.
b. Usar seu cartão de débito para uma refeição em um restaurante.
c. Comprar ações usando uma conta de corretagem on-line.
d. Procurar livros (sobre um assunto específico) usando uma livraria on-line.
e. Uma atividade especificada pelo seu professor.
5.10. O que representam as “exceções” nos casos de uso?
5.11. Descreva o que é um padrão de análise com suas próprias palavras.
5.12. Usando o modelo apresentado na Seção 5.5.2, sugira um ou mais padrões de análise
para os seguintes campos de aplicação:
a. Software contábil
b. Software de e-mail
c. Navegadores para a Internet
d. Software de processamento de texto
e. Software para criação de sites
f. Um campo de aplicação especificado pelo seu professor
5.13. Qual o significado de ganha-ganha no contexto das negociações durante uma ativida-
de de engenharia de requisitos?
5.14. O que você acha que acontece quando uma validação de req