Projeto de Implementação de Cloud AWS na Abstergo Empresa: Abstergo

Responsável pela Entrega: Márcio Alves

Data de Início da Implementação: 11/08/2025

Status: Planejamento

Introdução Atualmente, a infraestrutura de TI da Abstergo é inteiramente baseada em servidores locais (on-premises). Este modelo tradicional exige altos investimentos de capital (CapEx) para aquisição, atualização e manutenção de hardware, além de custos operacionais (OpEx) elevados com energia, refrigeração e pessoal dedicado ao gerenciamento da infraestrutura.

Este projeto propõe a adoção estratégica de serviços de computação em nuvem da Amazon Web Services (AWS) para modernizar nossas operações e, principalmente, otimizar nossa estrutura de custos. A migração para a nuvem nos permitirá substituir grandes investimentos de capital por despesas operacionais variáveis, pagando apenas pelos recursos que consumimos, enquanto ganhamos agilidade, escalabilidade e segurança para acelerar nossas pesquisas e o desenvolvimento de novos produtos.

Descrição do projeto A implementação será focada em três etapas, cada uma abordando um serviço AWS chave para resolver um desafio de custo específico que enfrentamos hoje.

Etapa 1 Nome da ferramenta: Amazon S3 (Simple Storage Service)

Foco da Ferramenta: Armazenamento de dados de alta durabilidade, escalabilidade e baixo custo.

Descrição do caso de uso: A Abstergo gera um volume massivo de dados (resultados de ensaios clínicos, dados genômicos, documentação de pesquisa, etc.) que hoje são armazenados em storages físicos caros. A migração desses dados para o Amazon S3 reduzirá os custos ao eliminar a necessidade de comprar novos discos e servidores de armazenamento, bem como os custos de manutenção e espaço físico associados. Utilizaremos as diferentes classes de armazenamento do S3 (como S3 Standard-IA para acesso infrequente e S3 Glacier para arquivamento de longo prazo) para garantir o menor custo possível, pagando apenas pelos gigabytes que utilizamos.

Etapa 2 Nome da ferramenta: Amazon EC2 (Elastic Compute Cloud)

Foco da Ferramenta: Fornecer capacidade computacional segura e redimensionável sob demanda.

Descrição do caso de uso: Nossas atividades de pesquisa, como modelagem molecular e simulações complexas, exigem um enorme poder de processamento (HPC - High-Performance Computing), mas de forma esporádica. Atualmente, mantemos um parque de servidores potentes e caros que permanecem ociosos na maior parte do tempo. Com o EC2, podemos provisionar centenas de máquinas virtuais para executar uma análise em poucas horas e desligá-las ao final do processo. A redução de custos é direta: trocamos um alto custo de capital fixo por um custo operacional flexível, pagando apenas pelo tempo de computação que realmente usamos.

Etapa 3 Nome da ferramenta: Amazon RDS (Relational Database Service)

Foco da Ferramenta: Simplificar a configuração, a operação e a escalabilidade de bancos de dados relacionais na nuvem.

Descrição do caso de uso: Nossos sistemas de gestão de laboratório (LIMS) e controle de ensaios clínicos dependem de bancos de dados que exigem gerenciamento constante (backups, atualizações de segurança, garantia de disponibilidade) pela nossa equipe de TI. Ao migrar esses bancos de dados para o Amazon RDS, a AWS automatiza essas tarefas operacionais. A redução de custos virá da otimização do tempo da nossa equipe, que poderá se dedicar a projetos de maior valor estratégico, e da diminuição do risco de paradas dispendiosas causadas por falhas de hardware ou erros humanos na administração dos bancos de dados.
