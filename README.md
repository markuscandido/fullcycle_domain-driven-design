# Domain Driven Design

Síntese do curso **Domain Driven Design**, parte integrante do [FullCycle 3.0](https://curso.fullcycle.com.br/curso-fullcycle/) by [Full Cycle](https://fullcycle.com.br/)

## Introdução

### Entendendo o Domain Driven Design (DDD): Clareza e Práticas para Projetos Complexos

O Domain Driven Design, ou simplesmente DDD, é frequentemente considerado uma abordagem "mística" pelos desenvolvedores. Embora muitos associem o DDD apenas a um conjunto de padrões de design, como agregados, repositórios e a tradicional separação de camadas de software, sua essência vai muito além disso. Neste artigo, vamos explorar como o DDD oferece uma maneira estruturada e poderosa de lidar com a complexidade de projetos de software maiores, proporcionando clareza e longevidade ao sistema.

**O que é DDD?**: Muitas vezes, ao tentar entender o DDD por meio das principais literaturas, o conceito pode parecer complexo e difícil de aplicar na prática. Isso acontece porque o DDD não é apenas um conjunto de práticas ou ferramentas, mas sim uma filosofia de desenvolvimento que requer um profundo entendimento do domínio, do contexto e das pessoas envolvidas no projeto.

O DDD é especialmente útil em projetos grandes e complexos, onde não temos clareza total sobre todos os aspectos do sistema desde o início. Ele não é adequado para sistemas simples ou pequenos, como o software de uma pequena loja local, mas sim para sistemas empresariais que precisam evoluir de maneira sustentável.

**DDD e Clareza**: A palavra que melhor define o DDD é "clareza". O objetivo principal do DDD é fornecer clareza tanto para o desenvolvedor quanto para o sistema como um todo. Isso significa garantir que as diferentes partes do sistema não se misturem de forma confusa e que o software seja projetado para durar e evoluir ao longo do tempo.

Muitas vezes, o termo "legado" é visto de maneira negativa, associando-se a um software difícil de manter e que causa problemas. No entanto, o DDD pode ajudar a mudar essa percepção. Um software legado bem estruturado deve ser visto como algo positivo, que reflete um trabalho bem-feito e que facilita a manutenção e evolução futura.

**DDD na Prática**: Aplicar o DDD envolve mais do que seguir um conjunto de regras ou padrões de projeto. Requer uma compreensão clara dos contextos e das necessidades da organização, além de um esforço consciente para manter a separação das responsabilidades dentro do sistema. A arquitetura resultante, quando bem-feita, permite que o software seja mantido e compreendido facilmente, mesmo após anos de uso e modificações.

**Conclusão**: O DDD é uma abordagem valiosa para o desenvolvimento de software de grande escala. Ele promove clareza, organização e sustentabilidade, desafiando a visão negativa associada ao software legado. A chave para aplicar DDD com sucesso está em compreender profundamente o domínio e o contexto do projeto, e em adotar uma mentalidade que valorize a clareza e a simplicidade na arquitetura de sistemas.

### Domain Driven Design (DDD): Origem, Princípios e Complexidade

O Domain Driven Design (DDD) é uma abordagem que, em sua essência, é fortemente conceitual. Quando se fala de DDD, é preciso estar preparado para um conteúdo denso e teórico, já que 70% de sua estrutura está relacionada a princípios de modelagem e não a código propriamente dito. O foco do DDD está em entender como o software deve ser modelado em torno do domínio da aplicação, que é o "coração" do sistema. Embora existam padrões práticos que ajudam no desenvolvimento, o DDD vai muito além de simples design patterns.

**O Que é DDD?**: DDD significa "Domain Driven Design" e é uma forma de desenvolver software com base na compreensão profunda das regras de negócio, dos processos e da complexidade do domínio. A ideia central é que a modelagem do software deve separar a complexidade natural do negócio daquela que é introduzida pelos desenvolvedores. Essa separação é fundamental para evitar que o software se torne confuso e difícil de manter.

A origem do DDD remonta ao livro de Eric Evans, publicado em 2003, que apresentou essa filosofia de desenvolvimento. Desde então, o DDD passou por fases de popularidade e ressurgiu com a adoção dos microsserviços, já que modelar a complexidade e separar contextos é um dos maiores desafios desse tipo de arquitetura. Assim, o DDD se encaixa perfeitamente, ajudando a evitar sistemas fragmentados de maneira inadequada.

**A Filosofia por Trás do DDD**: O mais importante no DDD não são os padrões de projeto, mas a filosofia que ele promove. Essa filosofia oferece uma visão mais madura e estratégica de como um desenvolvedor deve abordar a modelagem de um software. Ela vai além de simplesmente criar um banco de dados e implementar CRUDs (Create, Read, Update, Delete), estimulando o desenvolvedor a pensar nas regras de negócio e nos problemas que o sistema deve resolver.

A grande questão que o DDD aborda é a modelagem de problemas complexos, garantindo que o software seja desenvolvido com uma qualidade superior. Projetos que falham frequentemente sofrem de uma má modelagem, onde desenvolvedores e especialistas de domínio não falam a mesma língua. O DDD atua como uma ponte entre essas áreas, promovendo uma linguagem comum que todos entendem e utilizam no desenvolvimento.

**Leitura Essencial e Comunidade DDD**: O DDD gerou uma comunidade de entusiastas, pois seus princípios abordam problemas reais enfrentados por muitos desenvolvedores. Além do livro original de Eric Evans, existem outros textos importantes, como o de Vaughn Vernon, que oferece uma abordagem mais prática. Seu livro "Domain Driven Design Distilled" é uma introdução acessível ao DDD, mas é necessário ler também as obras mais completas para ter uma visão abrangente.

**Conclusão**: O DDD não é apenas uma série de práticas, mas sim uma filosofia de desenvolvimento focada em modelar a complexidade e o domínio da aplicação. Ele promove uma linguagem comum entre desenvolvedores e especialistas de negócio, facilitando a criação de software de alta qualidade. Embora existam várias literaturas sobre o tema, o entendimento prático e teórico do DDD continua sendo um dos fatores-chave para o sucesso em projetos de software complexos.

### Complexidade no Desenvolvimento de Software e o Papel do Domain Driven Design (DDD)

Quando se trata de desenvolvimento de software, a complexidade é uma realidade inevitável, especialmente em projetos maiores. O **Domain Driven Design (DDD)** surge como uma abordagem essencial para lidar com essa complexidade. No entanto, nem todos os sistemas precisam de DDD; ele é mais indicado para projetos de alta complexidade, onde existem múltiplas áreas, regras de negócio distintas e diversas equipes envolvidas. Sistemas simples, como os usados em pequenas empresas, geralmente não precisam dessa abordagem, pois a complexidade do domínio é baixa e soluções prontas ou "de prateleira" são suficientes.

**O Contexto Define a Complexidade**: Um dos maiores desafios em projetos complexos é a falta de clareza sobre o que cada parte do sistema faz e como as áreas da empresa se conectam. Em grandes corporações, diferentes departamentos muitas vezes falam "línguas" distintas, mesmo quando executam funções aparentemente semelhantes. Um exemplo disso é o termo "cobrança", que pode significar coisas muito diferentes dependendo do contexto de uma empresa.

O DDD ajuda a organizar essa complexidade, proporcionando uma visão clara das diferentes áreas e processos, além de garantir que todos os envolvidos, desde desenvolvedores até especialistas de domínio, estejam alinhados. Essa separação de contextos é fundamental para evitar mal-entendidos e garantir que o software represente adequadamente o negócio.

**A Importância de Técnicas Avançadas**: Projetos grandes e complexos exigem técnicas avançadas, como o DDD, para que possam ser bem-sucedidos. Simplificar demais um projeto com alta complexidade ou tratá-lo como um sistema simples de CRUDs inevitavelmente levará ao fracasso. Isso ocorre porque esses projetos envolvem políticas, departamentos, jargões específicos e, muitas vezes, a integração com sistemas legados ou soluções de prateleira. Ignorar essa complexidade e tentar implementar soluções simples resultará em sistemas falhos desde o início.

**A Complexidade de Software Não é Apenas Tecnológica**: Um dos pontos centrais ao discutir a complexidade de software é que grande parte dos problemas não surge da tecnologia em si, mas sim da **complexidade do negócio**. Como desenvolvedores, temos a tendência de focar nas ferramentas e frameworks a serem utilizados, como bancos de dados, arquiteturas e integrações em nuvem. No entanto, os maiores gargalos de um projeto geralmente estão relacionados à compreensão e modelagem das regras de negócio.

Por mais que a escolha da tecnologia seja importante, ela raramente é o principal motivo pelo qual um projeto falha. O verdadeiro problema geralmente está na falta de entendimento do domínio, na comunicação entre as equipes e na falta de clareza sobre as expectativas e os objetivos do sistema. O DDD busca exatamente resolver esses problemas, fornecendo uma estrutura para capturar e modelar a complexidade de negócios de maneira eficaz.

**A Complexidade Envolve Pessoas**: O desenvolvimento de software é profundamente impactado pelas pessoas envolvidas no processo. Desde os desenvolvedores até os especialistas de domínio, gerentes de produto e outros stakeholders, cada um tem uma visão própria do que o sistema deve fazer. Isso frequentemente resulta em conflitos ou mal-entendidos sobre como o software deve ser desenvolvido.

Sem técnicas adequadas para extrair e entender essas diferentes perspectivas, os desenvolvedores ficam presos entre demandas conflitantes, o que aumenta a complexidade do projeto. Essa falta de clareza na comunicação é uma das principais razões pelas quais muitos projetos falham. O DDD ajuda a mitigar esses problemas, proporcionando uma maneira de alinhar as expectativas e garantir que todos os envolvidos falem a mesma "língua".

**Conclusão**: A complexidade em projetos de software é inevitável, mas pode ser gerenciada de forma eficaz com o uso de **Domain Driven Design (DDD)**. O DDD oferece as técnicas necessárias para lidar com a complexidade de negócios e garantir que o software seja construído de forma a refletir fielmente o domínio da aplicação. Ele separa a complexidade técnica da complexidade do negócio e facilita a comunicação entre as diferentes áreas envolvidas no projeto.

Embora a tecnologia desempenhe um papel importante no desenvolvimento de software, o maior desafio está em entender e modelar corretamente o negócio. O DDD oferece a clareza necessária para navegar por esse terreno complexo, garantindo que o software atenda às necessidades do negócio de maneira eficiente e eficaz.

**Highlitghs**:

- DDD deve ser aplicado para casos de projetos de softwares complexos;
- Grandes projetos possuem muitas áreas, muitas regras de negócio, muitas pessoas com diferentes visões em diferentes contextos;
- Não hé como não utilizar técnicas avançadas em projetos de alta complexidade;
- Grande parte da complexidade desse tipo de software não vem da tecnologia, mas sim da comunicação, separação de contextos, entendimento do negócio por diversos ângulos;
- Pessoas

### Como o Domain-Driven Design (DDD) Pode Ajudar a Lidar com a Complexidade do Software

O desenvolvimento de software, especialmente em projetos complexos, vai além da escolha de tecnologias. Grande parte da complexidade de um software não está no lado técnico, mas no entendimento e na modelagem correta do negócio. É aí que o Domain-Driven Design (DDD) se torna uma ferramenta poderosa para auxiliar desenvolvedores a entender e resolver problemas de negócios de forma mais eficiente.

**Entendendo Domínios e Subdomínios**: O DDD propõe que o primeiro passo no desenvolvimento de um software complexo é entender o **domínio** do negócio, ou seja, a função principal que o software vai desempenhar. O domínio é o coração do software, o núcleo daquilo que estamos criando. Entretanto, raramente o domínio pode ser tratado de forma única. É necessário quebrá-lo em **subdomínios**, que são partes menores, mas igualmente importantes, que agregam valor ao negócio.

Ao decompor o problema em subdomínios, é possível focar na resolução de partes específicas do sistema, o que facilita a organização e implementação. Isso é especialmente útil em projetos onde diferentes áreas da empresa possuem regras de negócio e jargões distintos.

**Linguagem Universal: A Base do DDD**: Um dos pilares do DDD é o conceito de **linguagem ubíqua** ou **linguagem universal**, que visa garantir que todos os envolvidos no projeto — desenvolvedores, domain experts, e stakeholders — usem a mesma terminologia. Isso elimina mal-entendidos e garante que as funcionalidades sejam construídas de acordo com as necessidades reais do negócio.

Por exemplo, imagine que dois departamentos da empresa utilizem a palavra "cliente" de maneiras distintas. Um departamento considera o cliente como a pessoa que compra um produto, enquanto outro define cliente como uma empresa fornecedora. Se o software tratar esses dois "clientes" de maneira igual, surgirão problemas. O DDD ajuda a identificar essas diferenças e garantir que o contexto de cada termo seja claro e refletido no código.

**Estratégia e Tática no Design de Software**: Além de promover uma linguagem comum, o DDD também auxilia na criação de um **design estratégico** para o software. Isso significa mapear os domínios e subdomínios e organizar o projeto em **contextos delimitados** (Bounded Contexts). Cada contexto contém suas próprias regras de negócio e lógica, o que facilita o entendimento e a manutenção do software.

No entanto, o DDD não se limita à estratégia. Ele também fornece um **design tático**, que trata da implementação detalhada, como o uso de **entidades**, **objetos de valor** e **agregados**. Essas ferramentas ajudam a organizar as partes menores do sistema, garantindo que as interações entre elas sejam claras e robustas.

**Separando a Complexidade de Negócio da Tecnologia**: Um dos maiores desafios no desenvolvimento de software é separar a complexidade do negócio da complexidade técnica. Muitas vezes, desenvolvedores focam nas ferramentas tecnológicas antes de entender completamente o problema de negócio que precisam resolver. O DDD defende que o entendimento claro do negócio deve preceder a escolha das tecnologias.

Somente após modelar bem o domínio e subdomínios, é que as decisões técnicas como frameworks, banco de dados e arquitetura (como microsserviços ou monolito) devem ser tomadas. Isso garante que a tecnologia esteja a serviço do negócio e não o contrário.

**Conclusão**: O DDD não é apenas uma metodologia, mas um guia para ajudar desenvolvedores a enfrentarem a complexidade de sistemas de forma organizada e eficiente. Ele permite que o foco esteja no coração do problema, no domínio do negócio, e promove uma comunicação clara entre todos os envolvidos no desenvolvimento.

A adoção do DDD pode transformar o processo de desenvolvimento, garantindo que o software seja construído de acordo com as necessidades reais do negócio e que as decisões tecnológicas estejam alinhadas com esses objetivos. Em última análise, ele contribui para a criação de softwares mais sólidos, escaláveis e alinhados com o propósito da organização.

**Highlitghs**:

- Entender com profundidade o domínio e subdomínios da aplicação;
- Ter uma **linguagem universal** (linguagem ubíqua) entre todos os envolvidos;
- Criar o design estratégico utilizando Bounded Contexts;
- Criar o design tático para conseguir mapear e agregar as entidades e objetos de valor da aplicação, bem como os eventos de domínio;
- Clareza do que é complexidade de negócio e complexidade técnica

### Domain-Driven Design: A Essência da Modelagem de Domínios Complexos

O Domain-Driven Design (DDD) é frequentemente mal interpretado como uma abordagem voltada principalmente à organização de pastas ou estruturação de código. No entanto, sua verdadeira profundidade reside na habilidade de modelar o domínio de um negócio, levando em consideração as nuances e variações de linguagem entre diferentes departamentos e contextos.

**A Importância da Linguagem Ubíqua**: No coração do DDD está o conceito de **linguagem ubíqua**, que representa a comunicação clara e comum entre todos os envolvidos no projeto. Essa linguagem precisa ser modelada e incorporada dentro de **contextos delimitados**. Isso significa que, à medida que as conversas e termos usados pelos diferentes departamentos mudam, é um sinal claro de que estamos lidando com **contextos distintos**.

Por exemplo, quando um termo tem significados diferentes em áreas distintas da empresa, como "cliente" para o time de vendas e "cliente" para o time de compras, isso indica que há dois contextos diferentes, e a forma como o software é modelado para cada um deve refletir essa diferença.

**Contextos Delimitados: O Coração do DDD**: O DDD ensina que é fundamental **delimitar esses contextos** e desenvolver o software com base neles. Ao isolar os contextos, podemos garantir que cada parte do sistema é projetada de acordo com suas regras e terminologias específicas, evitando confusões e sobreposições.

Esses **contextos delimitados** (Bounded Contexts) podem se comunicar entre si, mas sua independência é crucial para manter a clareza e a organização. Ao entender e respeitar as fronteiras entre esses contextos, o desenvolvimento de software torna-se mais eficaz e compreensível.

**Complexidade em Escala**: Embora em projetos menores, como o sistema de uma padaria, o DDD não seja necessário, em sistemas maiores e complexos, ele pode ser a diferença entre o sucesso e o fracasso. A complexidade de grandes sistemas geralmente está no entendimento do negócio e na forma como a linguagem é usada. Sem uma modelagem correta desses aspectos, o projeto pode se tornar confuso e frustrante.

**Conclusão**: O DDD vai muito além de estruturas técnicas; ele foca em modelar o domínio do negócio de maneira que reflita sua realidade, separando claramente contextos e estabelecendo uma linguagem comum entre todos os envolvidos. A abordagem traz clareza para a construção de softwares complexos, ajudando a evitar confusões e a garantir que o desenvolvimento esteja alinhado com as necessidades do negócio. Para projetos grandes, essa clareza é essencial para o sucesso do software e para a sanidade dos desenvolvedores envolvidos.

## Domínios, subdomínios e contextos

### Domínio e Subdomínios no Domain-Driven Design: Explorando a Estrutura de Sistemas Complexos

No Domain-Driven Design (DDD), os conceitos de domínio e subdomínio são fundamentais para a estruturação e compreensão de sistemas complexos. A ideia central do DDD é permitir que o design de um sistema seja guiado pelo domínio, ou seja, pelas regras e pela lógica de negócios que são o coração da aplicação. No entanto, conforme o entendimento sobre o negócio evolui, fica claro que esse domínio pode ser dividido em subdomínios menores, cada um com um papel específico dentro da estrutura do sistema.

**O Processo de Exploração do Domínio**: Quando começamos a analisar o domínio, não é possível ter uma visão clara de toda a sua complexidade de imediato. Esse processo é comparado a entrar em um quarto escuro com uma lanterna, iluminando gradualmente partes do ambiente. Aos poucos, subdomínios distintos começam a emergir, permitindo uma organização mais clara das áreas de negócio que o software precisa atender.

Cada subdomínio representa uma área específica de complexidade ou problema dentro do domínio maior. Essa divisão ajuda a separar as diferentes responsabilidades e funcionalidades, facilitando o desenvolvimento e a manutenção do sistema.

**Tipos de Subdomínios**: No DDD, os subdomínios podem ser classificados em três categorias principais, dependendo de sua importância para o negócio:

1. **Core Domain (Domínio Principal)**: Este é o subdomínio mais importante, o "coração" do sistema. É onde reside o diferencial competitivo da empresa e o que justifica a existência do sistema. No exemplo de uma empresa que emite ingressos para eventos, o core domain seria o sistema de emissão de tickets, pois sem isso, o negócio não teria sentido. O core domain é o que faz o sistema único e valioso, e deve ser cuidadosamente modelado para garantir que entregue o máximo de valor.

2. **Subdomínio de Suporte**: Esses subdomínios são essenciais para o funcionamento do core domain, mas não geram o diferencial competitivo da empresa. Eles auxiliam no dia a dia das operações. Um exemplo seria um centro de distribuição em um e-commerce. Ele é vital para o negócio, pois permite a entrega dos produtos, mas não é o foco principal do sistema.

3. **Subdomínio Genérico**: Esses subdomínios oferecem funcionalidades necessárias, mas que podem ser facilmente substituídas ou terceirizadas. Eles não trazem vantagem competitiva significativa. Um exemplo comum seria o uso de um sistema de pagamento terceirizado, como uma gateway de pagamento. Embora necessário para o negócio, esse subdomínio não define o sucesso ou o diferencial da empresa.

**A Importância da Classificação de Subdomínios**: Compreender e classificar subdomínios é essencial para a modelagem eficiente de um sistema. Focar no core domain garante que os esforços de desenvolvimento estejam alinhados com as necessidades estratégicas do negócio. Subdomínios de suporte e genéricos podem ser tratados de forma diferente, com menor prioridade ou até terceirizados, permitindo que a equipe de desenvolvimento se concentre no que realmente importa para o sucesso do sistema.

**Conclusão**: Domínio e subdomínios são peças centrais no DDD e ajudam a estruturar sistemas complexos de forma eficiente. Ao entender e categorizar subdomínios corretamente, empresas podem criar soluções que não apenas resolvem problemas de negócio, mas também impulsionam seu diferencial competitivo. O DDD vai além de padrões de software e está profundamente enraizado na compreensão do domínio do negócio e na sua modelagem, oferecendo uma abordagem estratégica para o desenvolvimento de software.

**Highlights**:

- domínio e subdomínios
  - core domain:
    - coração do negócio
    - diferencial competitivo da empresa
  - support subdomain:
    - apoiam o domínio
    - faz a operação do domínio possível
  - generic subdomain:
    - softwares auxiliares
    - sem diferencial competitivo

### Espaço do Problema vs Espaço da Solução no Domain-Driven Design (DDD)

No Domain-Driven Design (DDD), um dos conceitos centrais é a distinção entre o **espaço do problema** e o **espaço da solução**. Entender essa diferenciação é essencial para criar um sistema bem estruturado e eficiente, permitindo que problemas complexos sejam divididos em partes gerenciáveis e que as soluções sejam planejadas de forma clara e organizada.

**Espaço do Problema**: O **espaço do problema** refere-se à visão geral do domínio e suas complexidades. Quando um desenvolvedor começa a trabalhar com DDD, ele primeiramente tenta entender o problema que o software precisa resolver. Isso envolve olhar para o domínio como um todo e identificar as diversas áreas de complexidade, que são então separadas em subdomínios menores. Esses subdomínios representam problemas específicos dentro do domínio maior.

Por exemplo, em um sistema de e-commerce, o domínio principal pode ser a operação de vendas online, mas ele pode ser dividido em subdomínios, como o gerenciamento de inventário, processamento de pagamentos, e logística de entrega. Cada um desses subdomínios tem suas próprias complexidades e desafios.

**Espaço da Solução**: Já o **espaço da solução** é onde o problema começa a ser resolvido. Depois de mapear o espaço do problema e entender os subdomínios, o próximo passo é trabalhar na modelagem do domínio. A modelagem de domínio é um dos pilares do DDD e envolve a criação de representações do domínio e de seus subdomínios no software, preparando-o para solucionar o problema identificado.

Um aspecto importante dessa modelagem é a delimitação de **contextos**. Cada subdomínio identificado no espaço do problema é transformado em um **contexto delimitado**, ou seja, uma área claramente definida no sistema onde aquele subdomínio específico será tratado. Esses contextos delimitados ajudam a organizar e priorizar o trabalho de desenvolvimento, garantindo que cada parte do problema seja abordada de forma isolada e clara.

**Da Modelagem à Solução**: No DDD, a transição do espaço do problema para o espaço da solução acontece através da modelagem cuidadosa e da divisão do domínio em subdomínios e contextos delimitados. Isso permite que os desenvolvedores organizem suas soluções de forma eficiente, atacando cada contexto delimitado de forma independente e garantindo que o sistema atenda às necessidades específicas do negócio.

Essa abordagem permite que problemas grandes e complexos sejam transformados em pedaços menores e mais gerenciáveis. Cada subdomínio pode ser tratado como um "mini problema" dentro do sistema maior, com soluções que são desenvolvidas e implementadas separadamente, mas que eventualmente se conectam para formar um sistema coeso e funcional.

**Conclusão**: O conceito de **espaço do problema** e **espaço da solução** no DDD ajuda a estruturar o processo de desenvolvimento, desde o entendimento das necessidades do negócio até a criação de um software que resolve essas necessidades de maneira organizada e eficaz. Dividir o problema em subdomínios e transformá-los em contextos delimitados é uma das estratégias fundamentais para garantir que soluções complexas sejam desenvolvidas com clareza e precisão. Essa é a essência do DDD: *transformar um problema de negócio em um software robusto por meio da modelagem do domínio*.

**Highlights**:

- problema vs solução
  - problema:
    - visão geral do domínio e suas complexidades
    - subdomínios
  - solução:
    - análise e modelagem do domínio
    - contextos delimitados

### O que é um Contexto Delimitado (Bounded Context) no Domain-Driven Design (DDD)

No Domain-Driven Design (DDD), o conceito de **contexto delimitado**, ou **bounded context**, é essencial para a organização e modelagem de sistemas complexos. Ele representa uma maneira de dividir explicitamente o domínio, delimitando fronteiras claras entre diferentes áreas do sistema.

**Definição de Contexto Delimitado**: Um **contexto delimitado** é uma divisão clara dentro do modelo de domínio. Essa divisão estabelece limites entre diferentes partes do sistema, ajudando a separar funcionalidades e responsabilidades de maneira estruturada. Cada contexto delimitado possui uma linguagem específica e única, chamada de **linguagem ubíqua** (ou linguagem onipresente), que reflete como os profissionais e o software dentro daquele contexto falam e resolvem problemas. A delimitação, portanto, não é apenas técnica, mas também reflete a forma como o negócio opera.

Por exemplo, em um sistema de grande escala, como uma "padaria industrial" com diversos departamentos (produção, vendas, atendimento ao cliente), cada área possui seu próprio vocabulário, processos e objetivos. A equipe que cuida da produção de pães tem um conjunto de termos e práticas diferentes da equipe de vendas ou da equipe de caixa. Isso sinaliza a presença de múltiplos contextos delimitados, onde cada um desses grupos opera com um modelo específico do domínio.

**Importância da Linguagem Ubíqua**: Um dos principais elementos que caracteriza um contexto delimitado é a **linguagem ubíqua**. Ela serve como um forte indicativo de que todos dentro daquele contexto estão "falando a mesma língua", utilizando os mesmos termos e conceitos para descrever os problemas e soluções dentro do domínio. Quando essa linguagem muda, é um sinal de que um novo contexto delimitado está sendo cruzado.

Por exemplo, em um sistema de e-commerce, o departamento de logística usa termos como "envio", "frete" e "armazém", enquanto o departamento de marketing pode falar sobre "campanhas", "conversão" e "tráfego". Cada um desses departamentos está inserido em seu próprio contexto delimitado, com suas próprias regras e terminologia.

**Quando o Contexto Delimitado é Necessário**: O conceito de contextos delimitados se torna mais relevante à medida que o sistema cresce em complexidade. Em sistemas pequenos, como um software básico de CRUD (Create, Read, Update, Delete), onde todos compartilham uma visão uniforme e uma linguagem comum, a aplicação de DDD pode não ser tão necessária. No entanto, em sistemas maiores e mais complexos, como indústrias ou grandes organizações, os contextos delimitados ajudam a organizar o desenvolvimento, isolando complexidades e evitando confusões entre diferentes áreas do negócio.

**Conclusão**: O **bounded context** é uma forma de estruturar sistemas complexos, estabelecendo fronteiras claras entre diferentes partes do domínio. Essas fronteiras são baseadas, em grande parte, na linguagem e nos processos específicos que cada área do negócio utiliza. Entender e identificar esses contextos delimitados é fundamental para aplicar o Domain-Driven Design de forma eficiente e evitar que um sistema complexo se torne desorganizado e difícil de gerenciar.

**Highlights**:

- bounded contexts:
  - é uma divisão explícita de um modelo de domínio existente

### Contexto é Rei no Domain-Driven Design (DDD)

No Domain-Driven Design (DDD), o conceito de **contexto** é central para a modelagem de sistemas complexos. Ele determina como diferentes áreas de uma empresa e seus respectivos problemas são representados no software. O conceito de "contexto é rei" ressalta que a mesma palavra ou conceito pode ter significados diferentes dependendo do contexto em que está inserido, e isso tem implicações diretas na forma como modelamos o domínio.

**A Importância do Contexto**: O **contexto** define os limites de significados dentro de um sistema. Quando um termo ou conceito, como "ticket", é usado em dois contextos diferentes, ele pode representar coisas completamente distintas. Por exemplo, no contexto de **venda de ingressos**, "ticket" refere-se a um bilhete de entrada para um evento. Já no contexto de **suporte ao cliente**, o "ticket" é uma solicitação de atendimento. Apesar de compartilharem o mesmo nome, suas funcionalidades e finalidades são completamente diferentes, demonstrando a importância de se trabalhar com **contextos delimitados**.

Se ambos os tipos de "ticket" fossem tratados de maneira unificada dentro de um sistema monolítico, haveria uma confusão de significados e funcionalidades. Isso resultaria em um design de software mal estruturado, com uma única entidade "ticket" sendo usada para duas finalidades completamente distintas. Para evitar isso, é essencial que o sistema reconheça e respeite esses diferentes contextos.

**Contextos Diferentes, Linguagens Diferentes**: Outro ponto chave é que **linguagem ubíqua**, ou a terminologia usada em um contexto, também varia de acordo com o departamento ou setor da empresa. Um exemplo disso pode ser visto na terminologia bancária: a área de **contabilidade** de um banco pode se referir a relatórios de boletos pagos como "relatórios financeiros", enquanto os funcionários de uma **agência bancária** podem chamar esses mesmos relatórios de "francesinhas". Embora representem a mesma informação, a diferença de terminologia indica que estamos lidando com dois contextos diferentes.

**Modularização Baseada em Contextos**: Um dos maiores desafios no desenvolvimento de software é garantir que o sistema esteja bem modularizado, de forma que cada **contexto** possa ser tratado de forma independente. Isso permite que um sistema cresça sem se tornar um monólito complexo e confuso. Cada contexto deve ter sua própria entidade, seus próprios modelos, e suas próprias regras, respeitando os limites do que ele deve representar.

**Conclusão**: No DDD, **"contexto é rei"** significa que o contexto sempre deve determinar como os termos são definidos e usados no sistema. Isso garante que cada parte do software represente de forma adequada as diferentes áreas de um negócio, evitando confusões e sobrecargas em entidades. Reconhecer e modularizar o sistema em diferentes contextos delimitados é fundamental para criar software flexível, adaptável e escalável.

**Highlights**:

- contexto é rei
  - ticket (vendas de ingressos)
  - ticket (suporte ao cliente)
  - duas palavras iguais com significados totalmente diferentes, são contextos claramente diferentes
  - duas palavras diferentes com significados iguais, são contextos diferentes
  - vendas de ingressos (cliente)
  - suporte ao cliente (cliente)

### Elementos Transversais e a Importância da Separação de Contextos no Desenvolvimento de Software

Ao modelar sistemas complexos no **Domain-Driven Design (DDD)**, um dos maiores desafios está em lidar com **elementos transversais**, ou seja, entidades que atravessam múltiplos contextos, como o conceito de "cliente". Embora um cliente possa existir em diferentes áreas de uma aplicação, suas responsabilidades e características variam de acordo com o contexto, e é fundamental que a modelagem de sistemas respeite essas variações para evitar complicações e confusões no código.

**A Complexidade dos Elementos Transversais**: No exemplo dado, um cliente pode estar presente tanto no contexto de **venda de ingressos** quanto no de **suporte ao cliente**. Apesar de ser o mesmo cliente, sua interação e os dados associados a ele são diferentes em cada um desses contextos. Na área de vendas, o foco está em informações como os **ingressos comprados**, os **eventos frequentados** e os **vendedores responsáveis**. Já no contexto de suporte, o cliente é visto de outra perspectiva, com foco em **tickets de atendimento**, **departamentos envolvidos** e **responsáveis pelo suporte**.

**O Problema da Modelagem Unificada**: Um erro comum no desenvolvimento de software é tentar modelar todas as interações de um cliente em uma única entidade, criando classes ou objetos gigantescos que tentam abarcar todos os contextos. Isso leva a um **crescimento descontrolado** da entidade "cliente", que passa a ter um conjunto de atributos e responsabilidades muito maior do que o necessário para cada contexto. Esse modelo unificado pode funcionar a curto prazo, mas, à medida que o sistema cresce e precisa se adaptar a novos requisitos, ele se torna difícil de manter e expandir.

Além disso, essa abordagem se torna um problema quando se decide migrar de um **sistema monolítico** para uma arquitetura de **microsserviços**. A entidade "cliente" que serve a todos os contextos precisará ser reescrita e fragmentada, tornando a migração muito mais complexa e trabalhosa do que se os contextos tivessem sido separados desde o início.

**A Necessidade de Múltiplas Entidades**: A solução proposta no DDD é modelar **entidades separadas** para cada contexto, mesmo que estejam relacionadas ao mesmo conceito. No caso do cliente, é perfeitamente aceitável — e recomendado — que existam diferentes entidades "cliente", cada uma adaptada ao seu contexto específico. Por exemplo, a entidade "cliente" no contexto de venda de ingressos deve conter apenas informações relevantes para esse processo, enquanto a entidade "cliente" no contexto de suporte terá outro conjunto de dados e funcionalidades.

Essa separação de contextos permite que o sistema seja mais modular, adaptável e escalável. Cada parte do sistema é desenvolvida para atender a uma função específica, sem sobrecarregar as entidades com dados e comportamentos desnecessários. Isso facilita também a eventual transição para microsserviços, pois cada serviço pode ser desenhado em torno de um contexto bem delimitado.

**Conclusão**: Os **elementos transversais**, como o cliente, ilustram a importância da separação de contextos no DDD. Mesmo que uma entidade esteja presente em diferentes áreas do sistema, suas interações e dados variam conforme o contexto, e essa diferenciação precisa ser refletida na modelagem do software. Criar entidades específicas para cada contexto evita que o sistema se torne um "monstro" difícil de manter, além de preparar o terreno para futuras expansões e migrações arquiteturais.

No próximo passo, uma abordagem prática para lidar com essa complexidade será o uso do **context mapping**, que ajudará a organizar e mapear as relações entre contextos e suas entidades.

**Highlights**:

- cliente
  - vendas de ingressos:
    - evento
    - ticket
    - local
    - vendedor
  - suporte ao cliente:
    - ticket
    - dúvida
    - departamento
    - responsável

## Visão estratégica

### Modelagem Estratégica e Context Mapping: Organizando a Complexidade do Desenvolvimento de Software

Ao iniciar o desenvolvimento de software utilizando **Domain-Driven Design (DDD)**, é crucial adotar uma visão estratégica e bem planejada. Essa abordagem envolve a compreensão clara dos domínios e como eles se relacionam, bem como a definição de contextos delimitados. Uma ferramenta essencial nesse processo é o **Context Mapping**, que ajuda a visualizar e organizar esses relacionamentos.

**O Papel da Modelagem Estratégica**: A modelagem estratégica tem o objetivo de fornecer uma visão geral de como os diferentes contextos de um sistema se encaixam. Durante a fase de análise, os desenvolvedores precisam identificar o **espaço do problema**, entendendo o domínio em que o software operará, para então começar a separar e delimitar os contextos. Esses contextos nem sempre são independentes — frequentemente eles interagem, se complementam e até colaboram.

Essa interação entre contextos requer uma abordagem estratégica que permita aos desenvolvedores entender como as **partes do sistema se comunicam** e se integram. Ao visualizar essas interações, torna-se mais fácil organizar o desenvolvimento e até mesmo definir como os times serão estruturados para lidar com diferentes áreas do sistema.

**O Que é Context Mapping?**: O **Context Mapping** é uma técnica que mapeia as interações entre os contextos delimitados. Ele permite uma visão de alto nível do sistema, ajudando a entender não apenas os limites de cada contexto, mas também como eles colaboram ou dependem uns dos outros. Essa ferramenta é fundamental para a fase inicial do desenvolvimento de software, quando o objetivo é organizar e planejar o sistema de maneira eficiente e escalável.

**Benefícios da Modelagem Estratégica**:

- **Clareza nas Interações**: Com o Context Mapping, fica mais fácil visualizar onde os contextos se conectam e como as informações são trocadas entre eles.
- **Organização de Times**: A modelagem estratégica ajuda a estruturar equipes de desenvolvimento com base nos contextos delimitados, permitindo que cada time foque em um conjunto específico de funcionalidades e interações.
- **Tomada de Decisões Informada**: Com uma visão clara dos contextos e suas interações, é possível tomar decisões mais precisas sobre a arquitetura do sistema, como a separação de microsserviços ou integração de APIs.
  
**Conclusão**: A modelagem estratégica, combinada com o Context Mapping, é essencial para o sucesso de projetos complexos de software. Ela oferece uma visão geral das interações entre contextos, ajudando a organizar o desenvolvimento e garantindo que o sistema seja escalável e modular. A abordagem estratégica permite que o desenvolvimento seja mais eficiente, evitando confusões e criando uma base sólida para a evolução do software.

### Context Mapping na Prática: Estruturando Relacionamentos Entre Contextos no Desenvolvimento de Software

No desenvolvimento de sistemas complexos, é comum lidar com diferentes áreas de um negócio que se inter-relacionam. O **Context Mapping**, uma técnica essencial no **Domain-Driven Design (DDD)**, ajuda a mapear essas interações, facilitando a organização dos times e o alinhamento das funcionalidades.

**Mapeando Contextos Delimitados**: Imagine um sistema de venda de ingressos online, onde o **core domain** é a venda de ingressos, mas há também áreas complementares, como suporte ao cliente, venda por parceiros e pagamentos. Cada uma dessas áreas representa um contexto delimitado, e o **Context Mapping** nos ajuda a visualizar como esses contextos se conectam e interagem.

**Relacionamentos Entre Contextos**: As interações entre contextos podem variar de acordo com as necessidades do negócio. Alguns exemplos de tipos de relacionamento são:

1. **Parceria (Partnership)**: Dois contextos, como a venda de ingressos online e a venda por parceiros, podem trabalhar juntos. Eles compartilham o objetivo de vender ingressos, e seus sistemas podem consumir APIs um do outro para realizar essas vendas.

2. **Shared Kernel**: Em alguns casos, dois contextos podem compartilhar um núcleo comum, como um SDK. No entanto, essa prática pode causar dependências indesejadas entre os sistemas, dificultando a manutenção.

3. **Cliente-Fornecedor (Upstream-Downstream)**: Um contexto fornece serviços para outro, como o sistema de pagamento fornecendo serviços à área de vendas de ingressos. O **upstream** dita as regras, e o **downstream** deve se adaptar.

4. **Conformista**: Quando um contexto consome um serviço externo, como uma gateway de pagamento, ele precisa se adaptar às regras impostas por esse serviço, sem poder influenciá-lo. Esse é um exemplo de relação conformista, em que o sistema deve se conformar com as limitações do fornecedor.

**Camada Anticorrupção (ACL)**: Para minimizar os impactos de uma relação conformista, é possível implementar uma **camada anticorrupção (ACL)**. Essa camada atua como um adaptador entre o sistema interno e o serviço externo, facilitando futuras mudanças de fornecedores sem a necessidade de modificar toda a lógica do sistema.

**A Importância do Context Mapping**: O **Context Mapping** oferece uma visão estratégica e clara das relações entre os contextos de um sistema, permitindo melhor organização de times e uma arquitetura mais robusta e escalável. Ele define quem fornece serviços, quem consome, e quais áreas trabalham em parceria, ajudando a evitar dependências problemáticas e facilitando a manutenção e evolução do sistema.

No próximo passo, o estudo de padrões comuns no **Context Mapping** aprofundará ainda mais essa prática, oferecendo dicas práticas e exemplos de implementações bem-sucedidas.

**Highlights**:

-

### Padrões de Context Mapping: Organizando Sistemas Complexos com DDD

No desenvolvimento de software utilizando **Domain-Driven Design (DDD)**, a técnica de **Context Mapping** permite organizar e entender a interação entre diferentes contextos de um sistema. No entanto, há diversos padrões que ajudam a estruturar essas relações, facilitando a modelagem estratégica e a comunicação entre as equipes. Vamos explorar alguns dos principais padrões e ferramentas que podem otimizar essa prática.

**Padrões Clássicos de Context Mapping**:

1. **Partnership (Parceria)**: Dois contextos trabalham em conjunto para atingir um objetivo comum, como times que compartilham funcionalidades para resolver problemas relacionados.

2. **Shared Kernel (Núcleo Compartilhado)**: Quando dois contextos compartilham uma parte do código, como uma biblioteca comum usada por ambos. Embora útil, pode causar dependências indesejadas entre sistemas.

3. **Customer-Supplier (Cliente-Fornecedor)**: Um contexto é o fornecedor de um serviço e o outro é o cliente que consome, seguindo uma relação de **upstream** (quem fornece) e **downstream** (quem consome). A comunicação e as melhorias no upstream impactam diretamente o downstream, que precisa se adaptar às mudanças.

4. **Conformista**: Em casos onde um sistema depende de um serviço externo, como uma API de pagamento, ele deve se conformar às regras impostas pelo fornecedor, sem possibilidade de alterá-las.

5. **Anti Corruption Layer (ACL)**: Para evitar que um sistema fique preso a um fornecedor específico, a **camada anticorrupção** atua como um adaptador, permitindo que o sistema interno continue funcionando mesmo que o fornecedor seja trocado.

6. **Open Host Service**: Um contexto que oferece um serviço público, exposto por meio de protocolos como APIs REST ou gRPC, para que outros sistemas possam consumi-lo facilmente.

7. **Published Language (Linguagem Publicada)**: Um contexto define uma linguagem padrão, como o formato de dados de uma API (ex: JSON), que outros sistemas devem usar para se comunicar com ele.

8. **Separated Ways (Caminhos Separados)**: Quando dois contextos não se comunicam mais e seguem caminhos independentes, mantendo seus próprios padrões e regras.

9. **Big Ball of Mud**: Um sistema desorganizado e sem padrões claros, onde diferentes funcionalidades e contextos estão misturados, tornando difícil a manutenção e evolução.

**Starter Kit para Context Mapping**: O projeto **DDD Crew/context-mapping** no GitHub oferece uma ferramenta visual poderosa para facilitar a aplicação dos padrões de context mapping. Ele fornece diagramas e cheat sheets que ilustram as relações entre os diferentes contextos e padrões, ajudando a criar mapas claros de sistemas complexos. Esse material pode ser utilizado em ferramentas colaborativas como o **Miro**, onde você pode começar a criar seus próprios mapas de contextos e estruturar suas relações.

**Utilizando o Context Mapping no Dia a Dia**: Ao adotar o **Context Mapping** e seus padrões, você está criando uma visão mais estratégica do sistema, ajudando a entender como diferentes áreas interagem, quem fornece serviços e quem consome, e como evitar dependências problemáticas. Embora o código seja uma parte importante do DDD, a separação de contextos e o mapeamento de suas interações são fundamentais para manter um sistema escalável e bem-organizado.

Essa abordagem proporciona uma base sólida para a modelagem de sistemas, permitindo a colaboração eficaz entre times e facilitando a manutenção e evolução de aplicações complexas.

**Highlights**:

- Padrões de Context Mapping:
  - Partnership
  - Shared Kernel
  - Customer-Supplier Development
  - Conformist
  - Anticorruption-layer
  - Open host service
  - Published language
  - Separate ways
  - Big ball of mud
- [github](https://github.com/ddd-crew/context-mapping)
