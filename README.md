Esse é o repositório central do projeto PTRF e as issues estão nele, mas ele é basicamente infra. O repositório da API em Django é esse:  [SME-PTRF-BackEnd](https://github.com/prefeiturasp/SME-PTRF-BackEnd) issues com a tag API viram PRs nele.
e o react é esse aqui:  [SME-PTRF-FrontEnd](https://github.com/prefeiturasp/SME-PTRF-FrontEnd) issues com a tag interface viram PRs nele.

# Pátio Digital

_“Recurso público retorna ao público”._

Nós somos o **pátio digital**, uma iniciativa da Secretaria Municipal de Educação de São Paulo que, por meio do fortalecimento da transparência, da participação social e do desenvolvimento de novas tecnologias, aproxima diferentes grupos da sociedade civil por um objetivo maior: a melhoria da educação na cidade de São Paulo.

# PTRF
Auxilia na gestão dos recursos repassados para as Associações de Pais e Mestres.

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
É uma aplicação digital que visa apoiar a execução do programa de transferência de recursos. Ele deve atender as necessidades dos usuários em três níveis de atuação: Escola/APM, DRE e SME.

### Personas
**Quem:** Escolas/APM  
Características Principais: Diretores das associações_  
Necessidades: Maior facilidade e transparência no processo de receber, gastar e prestar contas dos recursos do PRTF.  
  
**Quem:** DRE  
Características Principais: Técnicos das diretorias_  
Necessidades: Maior facilidade e transparência para acompanhar e validar a prestação de contas das associações e verificar os status de regularidade das mesmas.

**Quem:** SME  
Características Principais: Membros da secretaria  
Necessidades: Maior facilidade e transparência no recebimento de documentos e comunicação com DREs e Associações, além de automatização de processos como previsão do cálculo de repasses.

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

Inserir os links para os trabalhos de descoberta bem como uma explicação de cada etapa.

**Entrevista com a área de negócio:**



**Oficina:**



**Repositório de documentos produzidos:**



### Protótipos:
Inserir link para os protótipos construídos:

**Protótipo navegável da prestação de contas da Associação:** 

[https://www.figma.com/proto/iaOuJhddfKRep92yQmAWEi/PTRF-sprint03?node-id=1279%3A481&viewport=903%2C495%2C0.125&scaling=min-zoom](https://www.figma.com/proto/iaOuJhddfKRep92yQmAWEi/PTRF-sprint03?node-id=1279%3A481&viewport=903%2C495%2C0.125&scaling=min-zoom "https://www.figma.com/proto/iaOuJhddfKRep92yQmAWEi/PTRF-sprint03?node-id=1279%3A481&viewport=903%2C495%2C0.125&scaling=min-zoom")

**Protótipo navegável da Diretoria:** 

[https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=234%3A2499&viewport=1019%2C1832%2C0.125&scaling=min-zoom](https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=234%3A2499&viewport=1019%2C1832%2C0.125&scaling=min-zoom "https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=234%3A2499&viewport=1019%2C1832%2C0.125&scaling=min-zoom")

**Protótipo navegável do cálculo de repasses da Secretaria:** 

[https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=204%3A264&viewport=590%2C381%2C0.125&scaling=min-zoom](https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=204%3A264&viewport=590%2C381%2C0.125&scaling=min-zoom "https://www.figma.com/proto/6uptsXtau28gVruupqHibV/PTRF-sprint06?node-id=204%3A264&viewport=590%2C381%2C0.125&scaling=min-zoom")


### Testes de Usabilidade:
Inserir link para os testes de usabilidade aplicados:

**Testes realizados com o protótipo da Associação:**

[https://github.com/prefeiturasp/SME-DesignServicos/tree/master/docs/3-novas-demandas/PTRF/videos-teste-usabilidade-2020-05-03]
(https://github.com/prefeiturasp/SME-DesignServicos/tree/master/docs/3-novas-demandas/PTRF/videos-teste-usabilidade-2020-05-03
"https://github.com/prefeiturasp/SME-DesignServicos/tree/master/docs/3-novas-demandas/PTRF/videos-teste-usabilidade-2020-05-03")

**Anotações referentes aos testes realizados com o protótipo da Associação:**

[https://github.com/prefeiturasp/SME-DesignServicos/blob/master/docs/3-novas-demandas/PTRF/anotacoes-teste-prototipo.docx]
(https://github.com/prefeiturasp/SME-DesignServicos/blob/master/docs/3-novas-demandas/PTRF/anotacoes-teste-prototipo.docx
"https://github.com/prefeiturasp/SME-DesignServicos/blob/master/docs/3-novas-demandas/PTRF/anotacoes-teste-prototipo.docx")




## Links Úteis:

Inserir aqui o link para os ambientes utilizados pelo projeto:

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
