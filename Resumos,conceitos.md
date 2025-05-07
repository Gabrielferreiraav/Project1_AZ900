**1. O que é Computação em Nuvem?**

*   A computação em nuvem é definida como o **fornecimento de serviços de computação pela Internet**.
*   Esses serviços incluem infraestrutura de TI comum, como **máquinas virtuais, armazenamento, bancos de dados e rede**.
*   Vai além das ofertas de TI tradicionais, abrangendo serviços como **Internet das Coisas (IoT), Machine Learning (ML) e Inteligência Artificial (AI)**.
*   A nuvem permite **inovações mais rápidas, recursos flexíveis e economias de escala**.
*   Por utilizar a internet, não é limitada pela infraestrutura física da mesma forma que um datacenter tradicional.
*   Isso significa que, se você precisar aumentar sua infraestrutura de TI rapidamente, **não é necessário esperar a construção de um novo datacenter**; você pode usar a nuvem para **expandir rapidamente sua pegada de TI**.
*   É uma forma de **alugar poder computacional e armazenamento** do datacenter de outra pessoa. Você pode tratar recursos de nuvem como os do seu próprio datacenter, mas quando terminar de usá-los, você os devolve.
*   O provedor de nuvem se encarrega da **manutenção da infraestrutura subjacente**.

**2. Modelos de Nuvem**

*   Os modelos de nuvem **definem o tipo de implantação dos recursos de nuvem**.
*   Existem três modelos principais: **privado, público e híbrido**.
*   **Nuvem Privada:**
    *   Um ambiente de nuvem **criado por uma organização em seu datacenter**.
    *   Também pode ser hospedada em um **datacenter dedicado fora do local**, possivelmente por um terceiro.
    *   É **usada por uma única entidade**.
    *   As organizações são **responsáveis por operar os serviços** que fornecem.
    *   **Não fornece acesso a usuários fora da organização**.
    *   Oferece **maior controle para a empresa e seu departamento de TI** sobre recursos e segurança.
    *   Apresenta **maior custo e menos benefícios** em comparação com uma implantação de nuvem pública.
    *   O **hardware deve ser comprado** para inicialização e manutenção.
    *   As organizações são **responsáveis pela manutenção e pelas atualizações de hardware**.
    *   Os dados **não estão colocalizados com os dados de outras organizações**.
*   **Nuvem Pública:**
    *   **Construída, controlada e mantida por um provedor de nuvem de terceiros**.
    *   **Fornece recursos e serviços a várias organizações e usuários**.
    *   É **acessada via conexão de rede segura** (geralmente pela Internet).
    *   A **disponibilidade geral para o público** é uma diferença fundamental entre nuvens públicas e privadas.
    *   **Não há despesa de capital para escalar** verticalmente.
    *   Os aplicativos podem ser **provisionados e desprovisionados rapidamente**.
    *   As organizações **pagam apenas pelo que utilizam**.
    *   As organizações **não têm controle completo sobre recursos e segurança**.
*   **Nuvem Híbrida:**
    *   **Combina nuvens públicas e privadas em um ambiente interconectado**.
    *   Permite que os **aplicativos sejam executados no local mais adequado**.
    *   Pode ser usada para permitir que uma nuvem privada **lide com picos de demanda** implantando recursos de nuvem pública.
    *   Pode fornecer uma **camada extra de segurança**.
    *   Os usuários podem **escolher quais serviços manter na nuvem pública e quais implantar em sua infraestrutura de nuvem privada**.
    *   **Fornece a maior flexibilidade**.
    *   As organizações **determinam onde executar seus aplicativos**.
    *   As organizações **controlam a segurança, a conformidade e os requisitos legais**.
*   **Multi-cloud:**
    *   Um cenário cada vez mais provável que **usa vários provedores de nuvem pública**.
    *   Pode ocorrer por usar **diferentes recursos de diferentes provedores** ou por estar migrando.
    *   Envolve o **gerenciamento de recursos e segurança em ambos (ou mais) ambientes**.
*   **Azure Arc:**
    *   Um conjunto de tecnologias que **ajuda a gerenciar seu ambiente de nuvem**.
    *   Pode gerenciar ambientes no **Azure público, um datacenter privado, uma configuração híbrida ou mesmo um ambiente multi-cloud**.
*   **Azure VMware Solution:**
    *   Permite **executar cargas de trabalho VMware no Azure**.
    *   Proporciona integração e escalabilidade contínuas para usuários de VMware que desejam migrar para nuvem pública ou híbrida.

**3. Modelo Baseado no Consumo (CapEx vs. OpEx)**

*   Ao comparar modelos de infraestrutura de TI, há dois tipos de despesas a considerar: **Despesas de Capital (CapEx) e Despesas Operacionais (OpEx)**.
*   **CapEx:** É o **gasto inicial de dinheiro em infraestrutura física** (recursos tangíveis). As despesas de CapEx têm um valor que **se reduz com o tempo**.
*   **OpEx:** É o **gasto com produtos e serviços conforme necessário, pagamento conforme o uso**. Seja **cobrado imediatamente**.
*   A computação em nuvem **se enquadra em OpEx** porque opera em um modelo baseado no consumo.
*   Os provedores de serviços em nuvem operam em um **modelo baseado no consumo**, o que significa que os usuários finais **pagam somente pelos recursos que usam**.
*   Com a computação em nuvem, você **não paga pela infraestrutura física, eletricidade, segurança, etc., associados à manutenção de um datacenter**. Em vez disso, você paga pelos recursos de TI que usa. Se não usar nenhum recurso em um mês, não paga por nenhum.
*   Benefícios do modelo baseado no consumo:
    *   **Sem custos iniciais**.
    *   **Não há necessidade de comprar e gerenciar infraestrutura cara** que talvez não seja totalmente utilizada.
    *   A capacidade de **pagar por mais recursos quando são necessários**.
    *   A capacidade de **parar de pagar por recursos que não são mais necessários**.
*   Comparação com datacenters tradicionais: Em um datacenter tradicional, você tenta estimar as necessidades futuras de recursos. Se superestimar, gasta mais do que precisa. Se subestimar, seu datacenter atinge a capacidade rapidamente e o desempenho pode sofrer, sendo demorado corrigir (pedir hardware, instalar, adicionar energia/resfriamento/rede).
*   Na nuvem, você **não precisa se preocupar em acertar perfeitamente as necessidades de recursos**. Se precisar de mais máquinas virtuais, adicione-as. Se a demanda cair, remova máquinas conforme necessário. De qualquer forma, você **paga apenas pelas máquinas virtuais que usa**, não pela "capacidade extra" que o provedor de nuvem tem disponível.
*   O modelo pay-as-you-go ajuda a **planejar e gerenciar seus custos operacionais**, executar sua infraestrutura de forma mais eficiente e escalar conforme as necessidades do seu negócio mudam.
*   São fornecidos **preços para recursos e serviços individuais**. A **cobrança é feita com base no seu uso real**.

**4. Modelo de Responsabilidade Compartilhada**

*   Com o modelo de responsabilidade compartilhada, as responsabilidades pela segurança e manutenção na nuvem **são compartilhadas entre o provedor de nuvem e o consumidor**.
*   Em um datacenter corporativo tradicional, a empresa é **responsável por tudo**: espaço físico, segurança, servidores, infraestrutura, software, aplicação de patches, manutenção, etc..
*   Com a nuvem, essas responsabilidades mudam.
*   **O provedor de nuvem é sempre responsável por:**
    *   O **datacenter físico**.
    *   A **rede física**.
    *   Os **hosts físicos**.
    *   Segurança física, energia e refrigeração.
*   **O consumidor (você) é sempre responsável por:**
    *   As **informações e dados armazenados na nuvem**.
    *   Os **dispositivos que têm permissão para se conectar à nuvem** (celulares, computadores, etc.).
    *   As **contas e identidades** das pessoas, serviços e dispositivos dentro da sua organização.
    *   Segurança de acesso (garantir acesso apenas a quem precisa).
*   **A responsabilidade depende do Modelo de Serviço de Nuvem (IaaS, PaaS, SaaS) para:**
    *   Sistemas Operacionais.
    *   Controles de Rede.
    *   Aplicações.
    *   Identidade e infraestrutura.
*   O modelo IaaS (Infraestrutura como Serviço) **coloca a maior parte da responsabilidade no consumidor**, incluindo o gerenciamento de sistemas operacionais, aplicação de patches e manutenção.
*   O modelo SaaS (Software como Serviço) **coloca a maior parte da responsabilidade no provedor de nuvem**, que frequentemente lida com aplicação de patches e manutenção automaticamente.
*   O modelo PaaS (Plataforma como Serviço) é um **termo médio** que distribui a responsabilidade entre o provedor e o consumidor.
*   Um exemplo dado é que, ao usar um banco de dados SQL na nuvem (PaaS ou SaaS), o provedor cuida da manutenção do banco de dados, mas você é responsável pelos dados ingeridos. Se implantar uma máquina virtual e instalar um banco de dados SQL nela (IaaS), você seria responsável pelos patches/atualizações do banco de dados, além dos dados.

**5. Benefícios da Nuvem**

*   **Alta Disponibilidade:** Garante a **disponibilidade máxima**, independentemente de interrupções ou eventos. O Azure é um ambiente de nuvem altamente disponível com **garantias de tempo de atividade** (parte dos SLAs - Contratos de Nível de Serviço) dependendo do serviço.
*   **Escalabilidade:** Refere-se à capacidade de **ajustar recursos para atender à demanda**. Permite **adicionar mais recursos** para lidar com o aumento da demanda. Com a **escala vertical**, você pode adicionar CPUs ou RAM a uma máquina virtual para obter mais capacidade de processamento. Com a **escala horizontal** (ou expansão), você pode adicionar máquinas virtuais ou contêineres. Como a nuvem é baseada no consumo, você **não paga além do necessário** e pode **reduzir recursos e custos se a demanda cair**.
*   **Elasticidade:** A capacidade de **expandir ou reduzir recursos (automaticamente ou manualmente) em resposta a mudanças repentinas acentuadas na demanda**. Se houver um salto acentuado na demanda, os recursos podem ser expandidos horizontalmente (adicionando VMs ou contêineres). Da mesma forma, se houver uma queda significativa na demanda, os recursos podem ser reduzidos horizontalmente.
*   **Confiabilidade:** Devido ao design descentralizado, a nuvem **naturalmente suporta uma infraestrutura confiável e resiliente**. Permite ter **recursos implantados em várias regiões do mundo**. Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as **outras regiões ainda estarão em funcionamento**.
*   **Previsibilidade:** Permite que você avance com confiança no **desempenho** ou no **custo**, influenciada pelo Microsoft Azure Well-Architected Framework.
*   **Segurança:** A nuvem oferece **ferramentas de segurança**, mas a **implementação de muitas delas deve ser realizada pelo cliente**. O nível de controle de segurança do cliente depende do modelo de serviço: IaaS para controle máximo (gerenciamento de SO, patches), PaaS ou SaaS para aplicação automática de patches e manutenção.
*   **Governança:** A auditoria baseada em nuvem **ajuda a sinalizar recursos fora de conformidade** com seus padrões corporativos e fornece estratégias de mitigação. Patches de software e atualizações podem ser aplicados automaticamente dependendo do modelo operacional, o que ajuda na governança e segurança. Estabelecer uma presença de governança cedo ajuda a **manter sua presença de nuvem atualizada, protegida e bem gerenciada**.
*   **Gerenciabilidade:** Um dos principais benefícios são as **opções de capacidade de gerenciamento**. Existem dois tipos:
    *   **Gerenciamento de recursos na nuvem:** Escalar automaticamente a implantação de recursos com base na necessidade, implantar recursos a partir de um modelo pré-configurado.
    *   **Gerenciamento do ambiente de nuvem:** Gerenciar seu ambiente e recursos via **portal da Web, interface de linha de comando, APIs ou PowerShell**.

