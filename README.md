Esse é o repositório central do projeto PTRF e as issues estão nele, mas ele é basicamente infra. O repositório da API em Django é esse:  [SME-PTRF-BackEnd](https://github.com/prefeiturasp/SME-PTRF-BackEnd) issues com a tag API viram PRs nele.
e o react é esse aqui:  [SME-PTRF-FrontEnd](https://github.com/prefeiturasp/SME-PTRF-FrontEnd) issues com a tag interface viram PRs nele.

# Estratégia de Transformação Digital e Governo Aberto na SME

Como um governo pode atuar para garantir o bem comum de todos? Na SME, acreditamos que um dos meios para isso seja garantir transparência e prestação de contas e constante relação entre governo e sociedade para o desenvolvimento e implementação de políticas públicas. 

A Portaria SME nº 8.008, de 12 de novembro de 2018 oficializou a estratégia da Secretaria Municipal de Educação de SP para que nossas ações sejam pautadas nos princípios de Governo Aberto e para usarmos os valores e benefícios do mundo digital para melhorarmos nossos processos e serviços para os cidadãos. 
Com isso, pretendemos: 
- aumentar os níveis de transparência ativa e de abertura de dados, garantindo a proteção de dados pessoais; 
- instituir metodologias ágeis e colaborativas como parte do processo de desenvolvimento e de evolução de sistemas administrativos e de serviços digitais; 
- fortalecer o controle das políticas educacionais e da aplicação de recursos por parte da gestão e da sociedade; 
- promover espaços e metodologias de colaboração entre governo, Academia, sociedade civil e setor privado. 

O [Ateliê do Software](http://forum.govit.prefeitura.sp.gov.br/uploads/default/original/1X/c88a4715eb3f9fc3ceb882c1f6afe9e308805a17.pdf) é uma das ferramentas para operacionalização. Baseado em um modelo de contratação inspirado pelos movimentos ágil e de Software Craftsmanship, trabalhamos com equipes multidisciplinares para o desenvolvimento de produtos que beneficiam toda a comunidade escolar (técnicos da SME e DREs, gestores, professores, alunos e famílias) e concretizam os objetivos da Estratégia de Transformação Digital e Governo Aberto “Pátio Digital”.

# SIG-Escola
O Sistema Integrado de Gestão visa: a) apoiar os processos de gestão e prestação de contas de recursos financeiros das unidades educacionais da Rede Municipal de Educação de São Paulo, b) apoiar o acompanhamento e fiscalização dos referidos recursos pelas Diretorias Regionais de Educação e c) auxiliar na gestão e avaliação dos programas de transferência de recursos por parte da Secretaria Municipal de Educação. O Sistema inicialmente foi concebido para apoiar os processos de gestão e prestação de contas do Programa de Transferência de Recursos Financeiros (PTRF).

# PTRF
O Programa de Transferência de Recursos Financeiros (PTRF) foi instituído pela Secretaria Municipal de Educação em 2005, com objetivo de garantir maior autonomia às Unidades Educacionais. Os recursos são repassados às Associações de Pais e Mestres (APMs) e Associações de Pais e Mestres Servidores, Usuários e Amigos dos CEUs (APMSUAC), entidades responsáveis pelo recebimento, execução e prestação de contas dos recursos transferidos pela SME. A fiscalização da aplicação dos recursos financeiros é de responsabilidade das Diretorias Regionais de Educação e da Secretaria Municipal de Educação. Por meio do programa, a comunidade escolar participa do processo de decisão sobre o destino dos recursos repassados para manutenção e melhorias das Unidades Educacionais.

**Conteúdo:**
 1. [Sobre o Time](#Sobre-o-Time)
 2. [Sobre o Produto](#Sobre-o-Produto)
 3. [Como surgiu](#Como-surgiu)
 4. [Links Úteis](#Links-Úteis)
 5. [Comunicação](#Comunicação)
 6. [Como contribuir](#como-contribuir)
 7. [Repositórios](#Repositórios)
 8. [Documentações Auxiliares](#Documentações-Auxiliares)
 9. [Instalação e Configuração](#Instalação-e-Configuração)

---

## Sobre o Time:

<table>
<thead>
<tr>
<th>Papel</th>
<th>Titular</th>
<th>Suplente</th>
</tr>
</thead>
<tbody>
<tr>
<td>Product Owner</td>
<td>Ananda Grinkraut</td>
<td>Meire Cristina David</td>
</tr>
<tr>
<td>Agente de Governança</td>
<td>Filipe Pereira Nunes de Carvalho</td>
<td>Fernando Gonsales</td>
</tr>
<tr>
<td>Gerente de Projeto</td>
<td>Aline F. Pinto</td>
<td>-</td>
</tr>
<tr>
<td>Scrum Master</td>
<td>Marcos S. Nastri</td>
<td>-</td>
</tr>
<tr>
<td>Analista UX/UI</td>
<td>Giovanna Zanettim</td>
<td>-</td>
</tr>
<tr>
<td>Analista Programador</td>
<td>Alessandro Fernandes</td>
<td>-</td>
</tr>
<tr>
<td>Analista Programador</td>
<td>Anderson Marques</td>
<td>-</td>
</tr>
<tr>
<td>Analista Programador</td>
<td>Ollyver Ottoboni</td>
<td>-</td>
</tr>
</tbody>
</table>

## Sobre o Produto

### Objetivos de Negócio
O SIG-Escola é um sistema inteligente de gestão que permite que escolas, associações, DREs e SME tenham otimização do trabalho relativo à gestão dos recursos do PTRF, garantindo não apenas mais eficiência em todos os processos como também aumentando a transparência e possibilitando um trabalho baseado em análise de dados.

### Personas
**Quem:** Unidade Educacional/Associações 
Características Principais: Os usuários iniciais serão os Diretores das associações e mais um servidor por este indicado.  
Necessidades: Maior facilidade e transparência nos processos de gestão e prestação de contas dos recursos do PTRF.  
  
**Quem:** DRE  
Características Principais: Técnicos das diretorias_  
Necessidades: Maior facilidade e transparência para acompanhar e fiscalizar a prestação de contas das associações e verificar a situação de regularidade das mesmas.

**Quem:** SME  
Características Principais: Servidores da Secretaria Municipal de Educação
Necessidades: Aprimorar a gestão dos recursos do PTRF, facilitar e dar mais transparência no recebimento de documentos e comunicação com DREs e automatizar processos como a previsão de cálculo de repasses.

### Funcionalidades
**Ferramenta de apoio às Unidades Educacionais/Associações**
- Dados da associação;  
- Lançamento e acompanhamento dos créditos e despesas;  
- Painel de dados;  
- Central de notificações;  
- Geração dos documentos para a prestação de contas ( Demonstrativo financeiro, relação de bens e atas de apresentação da prestação de contas);  
  
**Ferramenta de apoio às Diretorias Regionais de Educação**
- Dados da diretoria;  
- Atribuição de técnicos as associações;  
- Consulta das associações, verificação da regularidade e acompanhamento da prestação de contas;  
- Gestão do processo de análise e fiscalização da prestação de contas;  
- Geração de relatórios consolidados para a SME;  
  
**Ferramenta de apoio à Secretaria Municipal de Educação**  
- Painel de dados;  
- Cálculo dos repasses;  
- Geração de relatórios;

### Jornadas
Descrever as principais jornadas de usuários

### Roadmap

<table class=MsoNormalTable border=0 cellspacing=0 cellpadding=0 width=708
       style='width:531.35pt;border-collapse:collapse'>
    <tr style='height:30.0pt'>
        <td width=179 style='width:134.45pt;border:solid windowtext 1.0pt;padding:
  0cm 3.5pt 0cm 3.5pt;height:30.0pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><b><span style='color:black'>ENTREGA</span></b></p>
        </td>
        <td width=217 style='width:163.0pt;border:solid windowtext 1.0pt;border-left:
  none;padding:0cm 3.5pt 0cm 3.5pt;height:30.0pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><b><span style='color:black'>ÉPICO</span></b></p>
        </td>
        <td width=312 style='width:233.9pt;border:solid windowtext 1.0pt;border-left:
  none;padding:0cm 3.5pt 0cm 3.5pt;height:30.0pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><b><span style='color:black'>FUNCIONALIDADE</span></b></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=179 rowspan=7 style='width:134.45pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>FASE 1 Ferramenta de Apoio às escolas</span></p>
        </td>
        <td width=217 rowspan=3 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Acesso, dados da Associação</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Acesso do usuário ao Sistema</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Dados da Associação</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Extração de dados</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=217 rowspan=3 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Painel de Ações, Despesas e Receitas</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Painel de Ações</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Gastos da Escola (Despesas da Associação)</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Entradas (Receitas da Associação)</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=217 style='width:163.0pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Prestação de contas</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Gerar documentos para a prestação de contas</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=179 rowspan=15 style='width:134.45pt;border-top:none;border-left:
  solid windowtext 1.0pt;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>FASE 2 - Apoio à Gestão e aprimoramento do
  apoio às escolas</span></p>
        </td>
        <td width=217 rowspan=2 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Apoio às DREs</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Painel de dados da DRE (dados das UEs
  agregados por DRE)</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Geração de relatório consolidado com os
  dados por DRE</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=217 rowspan=4 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Apoio à SME</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Painel de dados da SME (dados das UEs
  agregados para a SME)</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Geração de relatório consolidado com os
  dados da SME</span></p>
        </td>
    </tr>
    <tr style='height:51.0pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:51.0pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Integração com dados Eol - matrículas
  (Painel de dados escolas, DRE e SME - futuramente para o cálculo dos valores)</span></p>
        </td>
    </tr>
    <tr style='height:76.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:76.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Cálculo repasse - Disponibilização de
  campos com parâmetros a serem preenchidos para o cálculo do valor a ser
  repassado para cada APM, por tipo de ação e repasse (Parâmetros devem ser
  facilmente modificados)</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=217 rowspan=7 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Aprimoramento do apoio às Associações</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Impressão de telas</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Painel contas escola</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Navegação dos painéis</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Registro e visualização das modificações
  pelo usuário final</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Comunicação entre usuários</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Conferências automáticas do CNPJ</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Conferências automáticas da nota fiscal</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=217 rowspan=2 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Gestão de usuários</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Perfis de usuários</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Login e senha</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=179 rowspan=10 style='width:134.45pt;border-top:none;border-left:
  solid windowtext 1.0pt;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>FASE 3 - Integração de dados</span></p>
        </td>
        <td width=217 rowspan=2 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Importação de extrato bancário (API ou
  leitura de extratos)</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Importar dados do extrato bancário para o
  sistema</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Disponibilizar dados do extrato para a
  visualização da escola, categorização das despesas</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=217 rowspan=2 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Integração com o SOF</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Importar os dados do SOF (valores
  liquidados por escola, por DRE)</span></p>
        </td>
    </tr>
    <tr style='height:51.0pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:51.0pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Notificar eventuais equívocos no
  preenchimento do SOF, a partir da comparação com os valores calculados por
  unidade</span></p>
        </td>
    </tr>
    <tr style='height:51.0pt'>
        <td width=217 rowspan=4 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:51.0pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Integração com o SEI</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:51.0pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Upload dos comprovantes vinculados a
  despesas específicas (Mais de um documento por despesa)</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Categorização dos documentos comprobatórios
  (ex: pesquisa de preço, nota fiscal, ...)</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Notificações escolas (falta de documentos
  prestação de contas, prazos)</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Automatização da alimentação do processo
  SEI</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=217 rowspan=2 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Integração com o Sistema de Bens Patrimoniais</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Importação dos dados cadastrados no Sistema
  de Bens Patrimoniais</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Geração automática dos termos de doação</span></p>
        </td>
    </tr>
    <tr style='height:51.0pt'>
        <td width=179 rowspan=5 style='width:134.45pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 3.5pt 0cm 3.5pt;height:51.0pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>FASE 4 - Planejamento e fiscalização</span></p>
        </td>
        <td width=217 rowspan=3 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:51.0pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Fiscalização DREs</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:51.0pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Criação de marcadores para a checagem da
  prestação de contas das escolas (lançamento de despesas)</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Registro de adequações necessárias e
  adequações realizadas </span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Geração de relatório da análise da
  prestação de contas</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=217 rowspan=2 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Planejamento Associações</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Inserção do Plano de Ação Anual -
  relacionado com o planejamento da escola</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Planejamento gasto APM - cadastro de
  despesas planejadas</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=179 rowspan=5 style='width:134.45pt;border-top:none;border-left:
  solid windowtext 1.0pt;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>FASE 5 - Legado e comunicação</span></p>
        </td>
        <td width=217 rowspan=3 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Legado organizado</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Importação das bases de dados do legado do
  Programa</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Visualização e extração de dados (csv) do
  legado geral - DRE e SME</span></p>
        </td>
    </tr>
    <tr style='height:51.0pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:51.0pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Visualização simplificada do legado por
  unidade escolar (valores agregados repasse, despesa, saldo reprogramado)</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=217 rowspan=2 style='width:163.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Comunicação - publicização dos dados</span></p>
        </td>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Integração de dados com o portal SME:
  Escola Aberta / Página sobre o PTRF</span></p>
        </td>
    </tr>
    <tr style='height:25.5pt'>
        <td width=312 style='width:233.9pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 3.5pt 0cm 3.5pt;height:25.5pt'>
            <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='color:black'>Integração de dados com o Portal de Dados
  Abertos PMSP</span></p>
        </td>
    </tr>
</table>


## Como surgiu

### Fase de Descoberta:

O desenvolvimento da aplicação iniciou-se efetivamente em janeiro de 2020 e coincidiu com processos de redesenho do PTRF. A descoberta dos principais desafios e dificuldades do programa considerou: a) a proposta de revisão normativa realizada em 2017 por um Grupo de Trabalho da rede municipal, b) diagnóstico do Programa, a partir de entrevistas e análise de dados de sua execução, e c) estudos realizados em universidades sobre a descentralização de recursos financeiros para as unidades educacionais no município de São Paulo. 

Vale destacar que entre 2018 e 2019 várias iniciativas culminaram na ampliação do Programa e na necessidade de realização de adequações legais e normativas, sendo elas: a) a incorporação de novas ações: Volta às Aulas, Fazendo Futuro, Rolê Cultural, Grêmios Estudantil, Imprensa Jovem, Mais Escola e Formação; b) a transição do atual meio de pagamento – o cheque – pelo cartão de controle de despesas; e c) a migração dos processos para o Sistema Eletrônico de Informações. Apesar de sua importância para a manutenção das unidades educacionais e para a viabilização de parte de seus projetos pedagógicos, desde sua criação, há 14 anos, o Programa não passou por nenhum processo de atualização. 
Assim, concomitantemente ao desenvolvimento da aplicação para o Programa, tem-se revisto suas normativas de forma a modernizar e simplificar os procedimentos de uso e prestação de contas do PTRF. 

**Entrevista com a área de negócio:**
A primeira reunião entre as equipes do PTRF (DIACON/COPLAN/SME) e da AMcom, em conjunto com a COTIC/SME ocorreu em 16/01/2020. Em 24/01, a equipe da AMcom apresentou o primeiro desenho de produto, com base nas demandas e diagnóstico realizado pela SME.


**Oficina:**



**Repositório de documentos produzidos:**



### Protótipos:

**Protótipo navegável da prestação de contas da Associação:** 

[https://www.figma.com/proto/iaOuJhddfKRep92yQmAWEi/PTRF-sprint03?node-id=1279%3A481&viewport=903%2C495%2C0.125&scaling=min-zoom](https://www.figma.com/proto/iaOuJhddfKRep92yQmAWEi/PTRF-sprint03?node-id=1279%3A481&viewport=903%2C495%2C0.125&scaling=min-zoom "https://www.figma.com/proto/iaOuJhddfKRep92yQmAWEi/PTRF-sprint03?node-id=1279%3A481&viewport=903%2C495%2C0.125&scaling=min-zoom")

**Protótipo navegável da Diretoria:** 

[https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=234%3A2499&viewport=1019%2C1832%2C0.125&scaling=min-zoom](https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=234%3A2499&viewport=1019%2C1832%2C0.125&scaling=min-zoom "https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=234%3A2499&viewport=1019%2C1832%2C0.125&scaling=min-zoom")

**Protótipo navegável do cálculo de repasses da Secretaria:** 

[https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=204%3A264&viewport=590%2C381%2C0.125&scaling=min-zoom](https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=204%3A264&viewport=590%2C381%2C0.125&scaling=min-zoom "https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=204%3A264&viewport=590%2C381%2C0.125&scaling=min-zoom")


### Testes de Usabilidade:

**Testes realizados com o protótipo da Associação:**

[https://github.com/prefeiturasp/SME-DesignServicos/tree/master/docs/3-novas-demandas/PTRF/videos-teste-usabilidade-2020-05-03](https://github.com/prefeiturasp/SME-DesignServicos/tree/master/docs/3-novas-demandas/PTRF/videos-teste-usabilidade-2020-05-03 "https://github.com/prefeiturasp/SME-DesignServicos/tree/master/docs/3-novas-demandas/PTRF/videos-teste-usabilidade-2020-05-03")

**Anotações referentes aos testes realizados com o protótipo da Associação:**

[https://github.com/prefeiturasp/SME-DesignServicos/blob/master/docs/3-novas-demandas/PTRF/anotacoes-teste-prototipo.docx](https://github.com/prefeiturasp/SME-DesignServicos/blob/master/docs/3-novas-demandas/PTRF/anotacoes-teste-prototipo.docx "https://github.com/prefeiturasp/SME-DesignServicos/blob/master/docs/3-novas-demandas/PTRF/anotacoes-teste-prototipo.docx")


## Links Úteis:


**Homologação:**

[https://hom-sig.escola.sme.prefeitura.sp.gov.br/](https://hom-sig.escola.sme.prefeitura.sp.gov.br/)

**Produção:**

Não entrou em produção ainda.

## Comunicação:

| Canal de comunicação | Objetivos |
|----------------------|-----------|
| [Issues do Github](https://github.com/prefeiturasp/SME-PTRF/issues) | - Sugestão de novas funcionalidades<br> - Reportar bugs<br> - Discussões técnicas |
| [Telegram](https://t.me/patiodigital) | - Comunicar novidades sobre os projetos<br> - Movimentar a comunidade<br>  - Falar tópicos que **não** demandem discussões profundas |

## Como contribuir

Contribuições são **super bem vindas**! Se você tem vontade de construir o
curriculo digital conosco, veja o nosso [guia de contribuição](./CONTRIBUTING.md)
onde explicamos detalhadamente como trabalhamos e de que formas você pode nos
ajudar a alcançar nossos objetivos. Lembrando que todos devem seguir 
nosso [código de conduta](./CODEOFCONDUCT.md).

## Repositórios:

[SME-PTRF-BackEnd](https://github.com/prefeiturasp/SME-PTRF-BackEnd)

[SME-PTRF-FrontEnd](https://github.com/prefeiturasp/SME-PTRF-FrontEnd)


## Documentações Auxiliares:

Inserir link para a pasta de documentações ou algum material específico que tenha sido produzido.

## Instalação e Configuração para desenvolvimento:

### Para contribuir com o desenvolvimento da API

I)  Clone o repositório.
```console
$ git clone https://github.com/prefeiturasp/SME-PTRF-BackEnd.git back
$ cd back
```

II)  Crie um Virtualenv com Python 3.6
```console
$ python -m venv .venv
```

III.  Ative o Virtualenv.
```console
$ source .venv/bin/activate
```

IV.  Instale as dependências.
```console
$ pip install -r requirements\local.txt
```

V.  Configure a instância com o .env
```console
$ cp env_sample .env
```

VI.  Execute os testes.
```console
$ pytest
```

VII.  Faça um Pull Request com o seu desenvolvimento

## Executando com docker 

I. Clone o repositório
```console
$ git clone git@github.com:prefeiturasp/SME-PTRF-BackEnd.git back
```

II. Entre no diretório criado
```console
$ cd back
```

III. cp env_sample .env
```console
$ cp env-sample
```

IV. Execute o docker
```console
$ docker-compose -f local.yml up --build -d
```

V. Crie um super usuário no container criado
```console
$ docker-compose -f local.yml run --rm django sh -c "python manage.py createsuperuser"
```

VI. Acesse a url para verificar a versão (Faça o login primeiro com o usuário criado).
```console
http://localhost:8000/api/versao
```

### Filas Celery
**Subir o Celery Worker**
```console
$ celery  -A config worker --loglevel=info
```

**Subir o Celery Beat**
```console
$ celery  -A config beat --loglevel=info
```

**Monitorar os processos no celery**
```console
$ flower -A config --port=5555
```

**Limpar os processos no celery**
```console
$ celery  -A config purge
```

### Para contribuir com o desenvolvimento do front:

I) Clone o repositório.

```console
$ git clone https://github.com/prefeiturasp/SME-PTRF-FrontEnd.git front
$ cd front
```

II. Instale as dependências.

```console
$ npm i
```

III. Configure a instância com o .env

```console
$ cp env_sample .env
```

IV. Execute os testes.

```console
$ npm test
```

V. Execute a aplicação.

```console
$ npm start
```
