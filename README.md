# ProjetoBloco-TP1-Edemir_Ferreira_Junior
### (Principais pontos do CMMI, nível de maturidade - 1 a 5)
##### Representações do Modelo CMMI

O CMMI possui duas representações: a estagiada e a contínua. A representação
estagiada permite que as organizações melhorem um conjunto de processos
interrelacionados e, de forma incremental, tratem sucessivos conjuntos de PAs. A
representação contínua, por sua vez, permite que as organizações melhorem de forma
incremental os processos correspondentes a uma ou mais PAs. A empresa seleciona
em que áreas de processo ela será avaliada. 

##### Representação por Estágios

Esta representação preocupa-se com os processos da organização como um
todo, oferecendo uma abordagem estruturada e sistemática para a melhoria de um
estágio por vez. Atingir um estágio significa que uma estrutura de processo adequada
foi estabelecida como base para o próximo estágio [SEI 2006].
 As áreas de processo (PAs) são organizadas por níveis de maturidade – do
nível “inicial” (nível 1) ao nível “em otimização” (nível 5) – que sugerem uma ordem
para a implementação das áreas de processo. Cada nível possui várias PAs, e por sua
vez, cada PA possui objetivos, práticas genéricas e específicas, assegurando assim uma
base de melhoria adequada para o próximo nível de maturidade.

Na representação por estágios, quando uma organização atinge as práticas necessárias para estar em um nível, significa que atinge todos os requisitos necessários dos níveis imediatamente anteriores conforme ilustrado na Figura abaixo:

![CMMI](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/CMMI.png)

##### A) Nível 1 - Inicial.

É o nível de maturidade CMMI mais baixo. Em geral, as organizações desse nível têm processos imprevisíveis que são pobremente controlados e reativos. Nestes nível de maturidade não há PAs, os processos são normalmente imprevisíveis e caóticos, e a organização geralmente não fornece um ambiente estável.


##### B) Nível 2 - Gerenciado.

Neste nível, os projetos da organização têm a garantia de que os requisitos são gerenciados, planejados, executados, medidos e controlados. Quando essas práticas são adequadas, os projetos são executados e controlados de acordo com o planejado. O Gerenciamento de Projetos é o foco principal deste nível.


##### C) Nível 3 - Definido.

Nível em que todos os objetivos específicos e genéricos atribuídos para os níveis de maturidade 2 e 3 foram alcançados, os processos são mais bem caracterizados e entendidos e são descritos em padrões, procedimentos, ferramentas e métodos. O Foco neste nível é a padronização do processo.


##### D) Nível 4 - Quantitavamente Gerenciado.

Neste quarto nível, os objetivos específicos e genéricos atribuídos para os níveis de maturidade 2, 3 e 4 foram alcançados e os processos são medidos e controlados. O foco neste nível é o gerenciamento quantitativo.


##### E) Nível 5 - Em Otimização.

É o nível mais alto de maturidade CMMI, onde uma organização atingi todos os objetivos específicos atribuídos para os níveis de maturidade 2, 3, 4 e 5. Os processos são continuamente aperfeiçoados, considerando que a variação de um processo esta relacionada às interações, entre seus componentes tendo como foco principal a melhoria contínua do processo.


### (Uso do modelo em cascata)

No modelo em cascata original de Royce, as seguintes fases são seguidas em perfeita ordem:

Requerimento
Projeto
Implementação
Integração
Teste e depuração (verificação)
Manutenção de software

![Waterfall](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/Waterfall.png)

Para seguir um modelo em cascata, o progresso de uma fase para a próxima se dá de uma forma puramente sequencial. Por exemplo, inicialmente completa-se a especificação de requisitos — elaborando um conjunto rígido de requisitos do software (Por exemplo, os requisitos para minha rede social do TP1 (MercadoLivre e Clientes) 
devem permitir acesso através de Login e Senha, preenchimento de perfil do cliente, busca de produtos, chat para perguntas sobre o produto e campo para efetuar a compra, embora as especificações dos requisitos reais sejam mais detalhados, em um procedimento para projeto. Como o software sempre faz parte de um sistema (ou negócio) maior, o trabalho começa pelo estabelecimento de requisitos para todos os elementos do sistema e depois pela alocação de algum subconjunto desses requisitos para o software. Essa visão de sistema é essencial quando o software precisa interagir com outros elementos, tais como hardware, pessoas e bases de dados.

### (Problemas)

Entre os problemas às vezes encontrados quando se aplica o modelo cascata, temos:

1. Projetos reais raramente seguem o fluxo sequencial proposto pelo modelo. Embora o modelo linear possa conter iterações, ele o faz indiretamente. Como consequência, mudanças podem provocar confusão à medida que a equipe de projeto prossegue.

2. Frequentemente, é difícil para o cliente estabelecer explicitamente todas as necessidades. O modelo cascata exige isso e tem dificuldade para adequar a incerteza natural existente no início de muitos projetos.

3. O cliente deve ter paciência. Uma versão operacional do(s) programa(s) não estará disponível antes de estarmos próximos ao final do projeto. Um erro grave, se não detectado até o programa operacional ser revisto, pode ser desastroso.

Outro problema com essa abordagem é que, em geral, é fácil verificar se o código funciona direito, mas não é tão fácil verificar se os modelos e projetos estão bem escritos. Para ser efetivamente viável, esse tipo de ciclo de vida necessitaria de ferramentas de análise automatizada de diagramas e documentos para verificar sua exatidão, mas tais ferramentas ainda são bastante limitadas.

### (Requisitos de usuário)

Requisito de usuário são declarações, em uma linguagem natural somada a diagramas, dos serviços que se espera que o sistema forneça para os usuários e das limitações sob as quais ele deve operar. Esses requisitos podem variar de declarações amplas das características necessárias do sistema até descrições precisas e detalhadas da sua funcionalidade.

### (Montagem simples da rede social conforme o tema) URL para acesso

![Url](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/Url.png)

### 1) Então logo em seguida teremos ao clicar ENTER, a visualização da página (Tema escolhido)

![ML](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/Page%20ML.png)

### 2) Informe Login e senha para cadastrar (Requisitos: E-mail e 18 anos, caso contrário será negado cadastro)

![Login](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/Login.png)

### 3) Após login efetuado, temos a parte central do perfil

![InsidePage](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/Inside.png)

### 4) Temos então nossa parte para fazer anúncios e lançar Feeds

![Anuncio](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/PageVendasAnuncios.png)

### 5) Efetuando busca com nome de produto, teremos acesso a uma lista de produtos

![ListaProdutos](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/Lista%20de%20produtos.png)

### 6) Para perguntar algo sobre o produto, basta acessar o campo CHAT para fazer perguntas ao vendedor

![Chat](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/Chat.png)

### 7) Concluindo sua decisão e caso deseja comprar o produto, basta selecionar a opção de pagamento e verá um resumo do que esta comprando!

![EfetuarPagamento](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/EfetuarCompra.png)

### 8) Sistema pergunta como deseja pagar e apresenta opções

![ComoPagar](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/ComoPagar.png)

### 9) Opções aceitáveis de pagamento

![PagarOption](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/ComoPagar1.png)

### 10) Pagamento Efetuado, cliente recebe código de rastreio e aguarda e no prazo determinado recebe seu produto!

![RecebeProduto](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/RecebeuProduto.png)

## FIM








![HardCode](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/Final.gif)
