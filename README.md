# Relatório de Implementação de Serviços AWS - Abstergo Industries

## Informações Gerais
- **Data de Início:** 03 de Setembro de 2025  
- **Empresa:** Abstergo Industries  
- **Responsável:** Marcos Marciano

---

## Introdução
Este relatório apresenta o processo de implementação de ferramentas AWS na Abstergo Industries, realizado por Marcos Marciano.  
O objetivo principal foi selecionar **3 serviços AWS estratégicos** para reduzir custos operacionais imediatos, otimizar a infraestrutura de TI e melhorar a escalabilidade dos sistemas de distribuição farmacêutica.

---

## Descrição do Projeto
O projeto foi estruturado em 3 etapas críticas, cada uma abordando um aspecto específico da otimização de custos e performance.

### Etapa 1: Amazon EC2 Auto Scaling
- **Foco da ferramenta:** Escalabilidade automática de servidores  

**Caso de Uso:**  
A Abstergo Industries enfrenta picos sazonais de demanda devido a campanhas de vacinação e lançamentos de medicamentos.  
O EC2 Auto Scaling permite dimensionar automaticamente a capacidade de computação conforme a demanda real, eliminando a necessidade de manter servidores ociosos durante períodos de baixa atividade.  
A solução monitora métricas em tempo real e ajusta automaticamente o número de instâncias EC2.

- **Redução de Custos:** Até 40% em custos com infraestrutura computacional  
- **Benefício Adicional:** Melhoria de 99.9% na disponibilidade do sistema  

---

### Etapa 2: Amazon S3 Intelligent-Tiering
- **Foco da ferramenta:** Armazenamento otimizado de dados  

**Caso de Uso:**  
A empresa mantém grandes volumes de dados críticos, incluindo pedidos, registros de distribuição, documentação regulatória e dados transacionais.  
O **S3 Intelligent-Tiering** classifica automaticamente os dados em quatro camadas de acesso (Frequente, Infrequente, Arquivo Instantâneo e Arquivo Profundo) com base nos padrões de acesso, movendo-os entre camadas sem custos adicionais de recuperação.

- **Redução de Custos:** Até 70% em custos de armazenamento  
- **Benefício Adicional:** Eliminação da gestão manual de tiering de dados  

---

### Etapa 3: AWS Lambda
- **Foco da ferramenta:** Computação serverless sob demanda  

**Caso de Uso:**  
Processamento de pedidos, integrações com APIs de farmácias parceiras, geração de relatórios automáticos e validação de documentos fiscais foram migrados para funções Lambda.  
A solução executa código apenas quando necessário, com cobrança por milissegundo de uso, eliminando completamente custos com servidores ociosos.

- **Redução de Custos:** Até 90% em custos de processamento  
- **Benefício Adicional:** Redução do tempo de desenvolvimento de novas integrações  

---

## Conclusão
A implementação dessas soluções AWS na Abstergo Industries proporcionará:

- **Redução Imediata de Custos:** Diminuição significativa nos gastos com infraestrutura de TI  
- **Escalabilidade Automatizada:** Capacidade de responder rapidamente a flutuações de demanda  
- **Otimização de Recursos:** Eliminação de desperdícios com capacidade ociosa  
- **Conformidade Aprimorada:** Melhores práticas de segurança e disponibilidade  

**Recomendações futuras:**
- Expansão da adoção de Amazon RDS para gestão de bancos de dados relacionais  
- Uso do AWS Cost Explorer para monitoramento contínuo de custos  
- Revisões trimestrais com o AWS Well-Architected Framework  

---

## Anexos
- analise_custos_pre_pos.xlsx — Planilha comparativa de custos  
- manual_boas_praticas_aws.md — Documentação de *procedures*  
- roadmap_implementacao.pdf — Cronograma detalhado de migração
- Importante salientar que os arquivos em anexo são apenas ideias de possiveis arquivos que ajudariam na implementação da solução. Eles nao existem de fato.

Assinatura do ResponsÃ¡vel pelo Projeto:

Marcos Marciano
