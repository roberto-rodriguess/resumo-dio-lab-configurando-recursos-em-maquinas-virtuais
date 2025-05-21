# resumo-dio-lab-configurando-recursos-em-maquinas-virtuais

Este laboratório prático focou na exploração de recursos de computação no Microsoft Azure, demonstrando a criação e configuração de diversos serviços, com foco especial em máquinas virtuais.

### Máquinas Virtuais (VMs)

- Demonstração de criação de VMs com configurações predefinidas para diferentes ambientes (teste, produção)
- Explicação das opções de disponibilidade: zonas de disponibilidade e conjuntos de dimensionamento
- Discussão sobre famílias de VMs (séries B, D, F) e como selecionar o tamanho apropriado para diferentes cargas de trabalho
- Apresentação de instâncias spot do Azure, que oferecem descontos mas podem ser interrompidas quando outros usuários pagantes precisam dos recursos

### Configurações Importantes de VM

- Opções de escalabilidade automática: configuração de dimensionamento baseado em métricas como CPU
- Configuração de exclusão de recursos relacionados (discos, NICs, IPs) quando a VM é excluída para evitar "órfãos"
- Opções de backup e a importância de habilitá-los manualmente
- Configuração de desligamento automático e suas limitações (não há opção nativa para ligamento automático)

### Azure Virtual Desktop

- Explicação dos modelos de host: pessoal (dedicado) vs. em pool (compartilhado)
- Casos de uso para cada tipo: hosts pessoais para aplicações específicas/licenciadas, pools para maior economia
- Configuração de balanceamento e número máximo de usuários por host

### Azure Functions

- Criação de aplicativos de funções usando código ou containers
- Diferenças entre ambientes Windows e Linux baseados na linguagem escolhida
- Suporte a diversas linguagens de programação (Node.js, Java, Python, .NET)
