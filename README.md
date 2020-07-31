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
<td>-</td>
</tr>
<tr>
<td>Agente de Governança</td>
<td>???</td>
<td>???</td>
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
É uma aplicação digital que visa apoiar a gestão e prestação de contas inicialmente do Programa de Transferência de Recursos Financeiros (PTRF). Ele deve atender as necessidades dos usuários em três níveis de atuação: Unidade Educacional/Associação, DRE e SME.

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
**Ferramenta de apoio às associações**
- Dados da associação;  
- Lançamento e acompanhamento dos créditos e despesas;  
- Painel de dados;  
- Central de notificações;  
- Geração dos documentos para a prestação de contas ( Demonstrativo financeiro, relação de bens e atas de apresentação da prestação de contas);  
  
**Ferramenta de apoio às diretorias**
- Dados da diretoria;  
- Atribuição de técnicos as associações;  
- Consulta das associações, verificação da regularidade e acompanhamento da prestação de contas;  
- Gestão do processo de análise e fiscalização da prestação de contas;  
- Geração de relatórios consolidados para a SME;  
  
**Ferramenta de apoio à secretária**  
- Painel de dados;  
- Cálculo dos repasses;  
- Geração de relatórios;

### Jornadas
Descrever as principais jornadas de usuários

### Roadmap
Definir um roteiro de lançamento incremental, mostrando claramente os incrementos de MVP  
Estimar esforço por amostragem  
Calcular custos e especificar datas e cronograma de entrega



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
