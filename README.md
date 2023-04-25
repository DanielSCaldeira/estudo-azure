<p align="center">
    <img src="https://learn.microsoft.com/pt-br/media/learn/certification/badges/microsoft-certified-fundamentals-badge.svg" data-canonical-src="https://learn.microsoft.com/pt-br/media/learn/certification/badges/microsoft-certified-fundamentals-badge.svg" width="250" height="250"/> 
</p>

  <a href="https://learn.microsoft.com/pt-br/certifications/azure-fundamentals/?WT.mc_id=certposter_poster-wwl" target="_blank"> 
    <h1 align="center">
    Estudo Microsoft Certified: Azure Fundamentals
    </h1>
  </a>
  
  <p align="center">
    <a href="https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RWST4n#page=10" target="_blank"> 
    Trilha DEV
    </a>
&emsp; | &emsp;
    <a href="https://esi.microsoft.com/landing" target="_blank"> 
    Treinamento Microsoft
    </a>
 &emsp;|&emsp;
    <a href="https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE2PjDI" target="_blank"> 
    Certificações Microsoft
    </a>
&emsp; | &emsp;
    <a href="https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE2PjDI)
    [Documentação GITHUB](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images" target="_blank"> 
    Documentação git hub
    </a>
</p>

</br>
<a href="https://learn.microsoft.com/pt-br/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/" target="_blank"> 
    <h1 align="center"> Princípios básicos do Microsoft Azure: descrever os conceitos de nuvem</h1>
</a>

- O Azure também oferece novos recursos, como IA (inteligência artificial) e serviços focados em IoT (Internet das Coisas).

- Esse exame inclui três áreas de domínio de conhecimento
<p align="center">
    <img src="img/peso.png" data-canonical-src="img/peso.png" width="100%" height="auto"/> 
</p>

## Descrever a computação em nuvem

### O que é computação em nuvem?

</br>
A computação em nuvem é a entrega de serviços de computação pela Internet.Os serviços de computação incluem infraestrutura de TI comum, como máquinas virtuais, armazenamento, bancos de dados e rede, IoT (Internet das Coisas), ML (machine learning) e IA (inteligência artificial)

</br>

#### É sempre reponsavel o:

| PROVEDOR          | USUÁRIO                      |
| ----------------- | ---------------------------- |
| Datacenter físico | Dados que coloca no sistema  |
| Rede física       | Dispositivos que se conectam |
| Hosts físicos     | Usuários que têm acesso      |

</br>

#### O que é modelo de responsabilidade compartilhada?

</br>
Segurança física, energia, resfriamento e conectividade de rede são responsabilidade do provedor de nuvem já o consumidor é responsável pelos dados e pelas informações armazenados na nuvem e segurança de acesso

- IaaS (infraestrutura como serviço) o provedor de nuvem é responsável pelas questões básicas de segurança física, energia e conectividade, enquanto o consumidor tem a responsabilidade pela instalação, configuração, aplicação de patch, atualizações e segurança dos recursos de nuvem que aluga. Basicamente, o consumidor aluga o hardware em um datacenter de nuvem e decide como utilizar e gerenciar esses recursos.
  - Cenários comuns em que o IaaS faz sentido:
    - Migração lift-and-shift
    - Teste e desenvolvimento
  - Migração lift-and-shift:
    - Recursos de nuvem semelhantes aos do datacenter local
    - Migração dos elementos em execução local para execução na infraestrutura IaaS
  - Teste e desenvolvimento:
    - Estabelecimento de configurações para ambientes de desenvolvimento e teste
    - Necessidade de replicar rapidamente os ambientes estabelecidos
    - Ativação ou desativação rápida dos diferentes ambientes com uma estrutura de IaaS
    - Manutenção do controle completo sobre os ambientes

</br>

- PaaS (plataforma como serviço) está situado entre o IaaS e o SaaS e compartilha a responsabilidade entre o provedor de nuvem e o consumidor. O provedor de nuvem mantém os sistemas operacionais, bancos de dados e ferramentas de desenvolvimento.Dependendo da configuração, o provedor de nuvem ou o consumidor pode ser responsável pelas configurações de rede e conectividade, segurança de rede e aplicativo e infraestrutura de diretório.
  - Cenários comuns em que o IaaS faz sentido:
    - Estrutura de desenvolvimento:
      - O PaaS fornece uma estrutura para desenvolvedores criarem ou personalizarem aplicativos baseados em nuvem.
      - Reduz a quantidade de codificação necessária, pois os desenvolvedores podem usar componentes de software internos.
      - Inclui recursos de nuvem, como escalabilidade, alta disponibilidade e multilocação.
    - Análise ou business intelligence:
      - As ferramentas fornecidas como serviço com o PaaS permitem que as organizações analisem e minerem dados.
      - Encontrando insights e padrões e prevendo resultados para aprimorar previsões, decisões de design de produto, retornos sobre investimentos e outras decisões de negócios.

</br>

- SaaS (software como serviço) maior parte da responsabilidade no provedor de nuvem. Você está essencialmente alugando ou usando um aplicativo totalmente desenvolvido. Ele requer a menor quantidade de conhecimento técnico ou experiência para o emprego total.
  - Cenários comuns em que o SaaS faz sentido:
    - Email e mensagens.
    - Aplicativos de produtividade empresarial.
    - Controle de finanças e despesas.

</br>

#### Modelos de nuvem privado, público e híbrido.

 <p align="center">
    <img src="img/modelo-nuvem.png" data-canonical-src="img/modelo-nuvem.png" width="100%" height="auto"/> 
</p>

</br>

#### Azure Arc

O Azure Arc gerencia o ambiente de nuvem, seja uma nuvem pública exclusivamente no Azure, uma nuvem privada em seu datacenter, uma configuração híbrida ou até mesmo um ambiente de várias nuvens em execução em vários provedores de nuvem ao mesmo tempo.

</br>

#### Solução VMware no Azure

E se você já estiver estabelecido com o VMware em um ambiente de nuvem privada, mas quiser migrar para uma nuvem pública ou híbrida? A Solução VMware no Azure permite executar suas cargas de trabalho do VMware no Azure com integração e escalabilidade total.

</br>

## Modelo baseado em consumo

Existem dois tipos de despesas:CapEx (despesas de capital) e OpEx (despesas operacionais).

- A CapEx normalmente é uma despesa inicial única para comprar ou proteger recursos tangíveis.
- A computação em nuvem se enquadra na OpEx porque opera em um modelo baseado em consumo. Na computação em nuvem, você não paga pela infraestrutura física, pela eletricidade, pela segurança nem por nada que esteja associado à manutenção de um datacenter. Você paga pelos recursos de TI que usa. Se você não usar nenhum recurso de TI durante o mês, não pagará nada.

Um modelo baseado em consumo oferece vários benefícios, como:

- Sem custos prévios.
- Não há necessidade de comprar nem gerenciar uma infraestrutura cara que os usuários talvez não usem na capacidade máxima.
- A capacidade de pagar para obter mais recursos quando necessário.
- A capacidade de parar de pagar por recursos que não são mais necessários.

</br>

## Verificar seus conhecimentos

</br>
<p align="center">
    <img src="img/ex1.png" data-canonical-src="img/ex1.png" width="100%" height="auto"/> 
</p>
</br>

## Descrever os benefícios do uso de serviços de nuvem

</br>
O tempo de atividade (ou disponibilidade) e a capacidade de lidar com a demanda (ou a escala).

- Alta disponibilidade: se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.
- Escalabilidade: significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.

A escala geralmente vem em duas variedades: vertical e horizontal.

- Dimensionamento vertical: Maior capacidade de processamento adicionar mais CPUs ou RAM
- Dimensionamento horizontal: Replicando a aplicação por exemplo em container ou maquina virtuais.

</br>

## Descrever os benefícios da confiabilidade e da previsibilidade na nuvem

Confiabilidade e previsibilidade são dois benefícios cruciais na nuvem que ajudam você a desenvolver soluções com confiança.

- Confiabilidade:

  - Resiliência é a capacidade que um sistema tem de se recuperar de falhas e continuar funcionando. Ela também é um dos pilares do `Microsoft Azure Well-Architected Framework`.
  - Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo.

- Previsibilidade: Obtem a previsibilidade do custo e desempenho. Ao implantar uma solução criada com base nessa estrutura `Microsoft Azure Well-Architected Framework`, você tem uma solução com custo e desempenho previsíveis.

- Desempenho: A previsibilidade de desempenho se concentra em prever os recursos necessários para oferecer uma experiência positiva aos clientes. Exemplo: dimensionamento automático, balanceamento de carga, alta disponibilidade e etc.

- Custo: A previsibilidade de custos se concentra em prever o custo dos gastos com a nuvem. Monitorando os recursos e custo para poder tomar decisões. Você pode até mesmo usar ferramentas como TCO (custo total de propriedade) ou a Calculadora de Preços para obter uma estimativa de possíveis gastos com a nuvem
  </br>

## Descrever os benefícios da segurança e da governança na nuvem

1. Suporte à governança e conformidade:
   - Recursos de nuvem ajudam a garantir que todos os recursos implantados atendam aos padrões corporativos e regulatórios.
   - Modelos de conjunto e auditoria baseada em nuvem sinalizam recursos que estejam fora de conformidade e fornecem estratégias de mitigação.
   - É possível atualizar todos os recursos implantados com novos padrões à medida que os padrões são alterados.
2. Soluções de segurança personalizáveis:
   - Infraestrutura como serviço fornece recursos físicos, mas permite que você gerencie sistemas operacionais e software instalado, incluindo aplicação de patches e manutenção.
   - Plataforma e software como serviço oferecem a opção de tratamento automático de patches e manutenção.
3. Proteção contra ataques DDoS:
   - Os provedores de nuvem são adequados para lidar com situações como ataques de DDoS, tornando a rede mais robusta e segura.
4. Importância da presença de governança na nuvem:
   - Estabelecer uma presença de governança o mais cedo possível ajuda a manter a presença de nuvem atualizada, protegida e bem gerenciada.

</br>

### Tipos de capacidade de gerenciamento para computação

Recursos de gerenciamento da nuvem:

- Escalabilidade automática de recursos com base na necessidade.
- Implantação de recursos com base em modelos pré-configurados, removendo a necessidade de configuração manual.
- Monitoramento da integridade dos recursos e substituição automática de recursos com falha.
  Recebimento de alertas automáticos com base em métricas configuradas para obter desempenho em tempo real.

Opções de gerenciamento na nuvem:

- Gerenciamento por meio de um portal da web.
- Gerenciamento usando uma interface de linha de comando.
- Gerenciamento usando APIs.
- Gerenciamento usando o PowerShell.

## Verificar seus conhecimentos

</br>
<p align="center">
    <img src="img/ex2.png" data-canonical-src="img/ex2.png" width="100%" height="auto"/> 
</p>
</br>

## Verificar seus conhecimentos

</br>
<p align="center">
    <img src="img/ex3.png" data-canonical-src="img/ex3.png" width="100%" height="auto"/> 
</p>
</br>

<a href="https://learn.microsoft.com/pt-br/training/paths/azure-fundamentals-describe-azure-architecture-services/" target="_blank"> 
    <h1 align="center"> Conceitos básicos do Azure: descrever a arquitetura e os serviços do Azure</h1>
</a>

## Descrever os principais componentes arquitetônicos do Azure
