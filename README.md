# Desafio DIO GFT - AWS 
## Relatório de Implementação de serviços AWS  

Data: 06/08/2025 

Nome: Livia Moreira Rocha 

## Introdução  
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Livia Moreira Rocha. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos, aumentar a eficiência operacional e modernizar a infraestrutura de tecnologia que suporta as aplicações da companhia.  

 ### Desafio do Projeto  
Inicialmente vamos elencar desafios operacionais dentro de uma Farmácia com loja física e vendas online.  
 * Controle de estoque e validade: risco de perdas por vencimento e ruptura de produtos essenciais  
 * Descontos dinâmicos: variações diárias de preços e promoções exigem atualização em tempo real  
 * Notas fiscais e receituários especiais: exigem conformidade legal e armazenamento seguro  
 * Alertas de compras virtuais: necessidade de resposta rápida a pedidos online  
 * Prazo de entrega: rastreabilidade e previsibilidade logística  
 * Controle financeiro: visibilidade de custos, faturamento e margem por produto  
 * Sincronização entre estoque físico e online  
 * Gestão de pedidos multicanal (balcão, app, site)  
 * Notificações em tempo real para clientes e equipe  
 * Segurança de dados sensíveis (receitas, pagamentos)  
 * Alta disponibilidade em períodos de pico (promoções, campanhas)  

 ### Descrição do Projeto 
Modernizar a operação de uma farmácia com loja física e vendas online, utilizando três ferramentas da AWS para enfrentar desafios operacionais e escalar com eficiência.  

### Etapa 1:  
- Nome da Ferramenta: Amazon S3 (Simple Storage Service)  
- Foco da ferramenta: Armazenamento seguro e escalável de dados  
Caso de uso: Armazenamento de notas fiscais eletrônicas, receituários digitais e documentos regulatórios,
Backup automático de relatórios financeiros e históricos de vendas,
Integração com sistemas de ERP para consulta rápida e segura.

Desafio resolvido: Evita perda de documentos, facilita auditorias e garante conformidade com a legislação  
Ganho: Redução de custos com servidores físicos e aumento da segurança de dados  

### Etapa 2:  
- Nome da Ferramenta: AWS IoT Core  
- Foco da ferramenta: Monitoramento em tempo real de dispositivos e sensores  
Caso de uso: Controle de estoque com sensores de temperatura e validade de medicamentos,  
Alertas automáticos para produtos próximos do vencimento,  
Integração com balanças e leitores RFID para rastrear entrada e saída de produtos.  

Desafio resolvido: Minimiza perdas por vencimento e alteração de temperatura, melhora a acurácia do estoque e agiliza reposição  
Ganho: Redução de desperdício e aumento da eficiência logística  

### Etapa 3:  
- Nome da Ferramenta: Amazon QuickSight  
- Foco da ferramenta: Business Intelligence e visualização de dados  
Caso de uso: Análise de vendas por canal (loja física vs online),  
Monitoramento de campanhas promocionais e descontos dinâmicos,  
Relatórios financeiros e de entrega em tempo real.  

Desafio resolvido: Decisões mais rápidas e baseadas em dados, controle de margem e rentabilidade  
Ganho: Otimização de campanhas, aumento de conversão e controle financeiro mais preciso. 

## Conclusão 
### Estratégia de Escalabilidade  
Loja física: Sensores IoT e armazenamento local sincronizado com a nuvem  
E-commerce: Infraestrutura elástica com EC2 e S3 para lidar com picos de acesso  
Backoffice: BI com QuickSight e automações com Lambda para relatórios e alertas  

### Redução de Custos  
Eliminação de servidores locais e manutenção física  
Redução de perdas por vencimento e estoque mal gerenciado  
Otimização de campanhas e descontos com base em dados reais  

### Ganhos Operacionais  
Mais agilidade na tomada de decisão  
Conformidade regulatória garantida  
Experiência do cliente aprimorada com alertas e entregas mais rápidas  

------ 
Assinatura do projeto: Livia Moreira Rocha 
