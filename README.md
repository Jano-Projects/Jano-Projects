<div align="center">

# Projeto Jano

**Software livre, local e documentado em português.**

Ferramentas que rodam no seu computador, com código aberto para usar, estudar e modificar.
Mantido por **Victor H. Correa**, desenvolvedor Oracle PL/SQL.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-victor--hsc-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-hsc)
![Idioma](https://img.shields.io/badge/idioma-português-2E7D32?style=flat-square)
![Uso](https://img.shields.io/badge/uso-gratuito-555555?style=flat-square)
![Código](https://img.shields.io/badge/código-aberto%20(MIT%20·%20GPL--3.0)-37474F?style=flat-square)
![Execução](https://img.shields.io/badge/execução-local-0E6B5A?style=flat-square)

</div>

---

## Sumário

- [Projetos](#projetos)
- [Aprendiz](#aprendiz)
- [Calculadora RTC Fácil](#calculadora-rtc-fácil)
- [Observatório de Pontualidade Aérea](#observatório-de-pontualidade-aérea)
- [HONK!](#honk)
- [Plataformas](#plataformas)
- [Autoria e identidades nos repositórios](#autoria-e-identidades-nos-repositórios)
- [Princípios](#princípios)

---

## Projetos

| Projeto | Para quem | O que faz | Tecnologia |
|---|---|---|---|
| [**Aprendiz**](#aprendiz) | Estudantes e desenvolvedores de IA | Assistente pessoal offline que responde só com o que você ensina a ele, mostrando cada etapa do que pensa. | Python |
| [**Calculadora RTC Fácil**](#calculadora-rtc-fácil) | Empresas, contadores e equipes de ERP | CBS, IBS e Imposto Seletivo da Reforma Tributária com a calculadora oficial da Receita Federal, numa tela simples. | Java, JavaScript |
| [**Observatório de Pontualidade Aérea**](#observatório-de-pontualidade-aérea) | Analistas de dados e desenvolvedores Oracle | Pontualidade das companhias aéreas a partir dos dados abertos da ANAC, com aplicação web e API REST. | Oracle PL/SQL, APEX |
| [**HONK!**](#honk) | Quem gosta de jogos e quem estuda SQL | Roguelite cômico em xilogravura de cordel: um ganso acordou com ódio. O motor do jogo é um banco de dados. | SQL (DuckDB-WASM), JavaScript |

---

## Aprendiz

Assistente pessoal **local e offline**. Responde exclusivamente com base no conhecimento fornecido pelo próprio usuário: não coleta dados, não acessa a internet e funciona inclusive em máquinas com poucos recursos. Todo o código é comentado em português, para servir também como material de estudo de Processamento de Linguagem Natural e aprendizado de máquina.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Offline](https://img.shields.io/badge/execução-100%25%20offline-37474F?style=flat-square)
![PLN](https://img.shields.io/badge/área-PLN-6A1B9A?style=flat-square)
[![Versão](https://img.shields.io/github/v/release/Jano-Projects/aprendiz-dev?style=flat-square&label=versão&color=4f46e5)](https://github.com/Jano-Projects/aprendiz-dev/releases/latest)

| Repositório | Conteúdo | Atividade |
|---|---|---|
| [**aprendiz-dev**](https://github.com/Jano-Projects/aprendiz-dev) | Código-fonte do aplicativo, integralmente comentado. | ![Último commit](https://img.shields.io/github/last-commit/Jano-Projects/aprendiz-dev?style=flat-square&label=atualizado) |
| [**aprendiz-addons**](https://github.com/Jano-Projects/aprendiz-addons) | Loja oficial de addons: bases de conhecimento prontas para importar no aplicativo. | ![Último commit](https://img.shields.io/github/last-commit/Jano-Projects/aprendiz-addons?style=flat-square&label=atualizado) |

<details>
<summary><b>Algoritmos implementados</b></summary>

| Técnica | Finalidade |
|---|---|
| BM25 | Ranqueamento de documentos por relevância |
| TF-IDF | Ponderação de termos |
| Naive Bayes | Classificação de intenção |
| Distância de Levenshtein | Tolerância a erros de digitação |
| Reciprocal Rank Fusion (RRF) | Combinação de resultados de múltiplas buscas |
| TextRank | Extração e sumarização de trechos relevantes |
| Regressão logística | Busca calibrada, com pesos aprendidos a partir de perguntas reais |

</details>

---

## Calculadora RTC Fácil

Interface amigável para a [calculadora oficial da Reforma Tributária do Consumo](https://github.com/ReceitaFederal/calculadora-rtc-regime-regular) (LC 214/2025), da Receita Federal. Abre com **um clique**, sem instalar Java, Git ou qualquer outra coisa antes, e **se atualiza sozinha**: quando a Receita publica uma versão nova, ela é baixada, compilada e colocada em uso sem interromper quem está usando. Os cálculos rodam no próprio computador.

![Java](https://img.shields.io/badge/Java%2025-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Área](https://img.shields.io/badge/área-tributário-0E6B5A?style=flat-square)
[![Versão](https://img.shields.io/github/v/release/Jano-Projects/calculadora-rtc-facil?style=flat-square&label=versão&color=0E6B5A)](https://github.com/Jano-Projects/calculadora-rtc-facil/releases/latest)
[![Testes](https://img.shields.io/github/actions/workflow/status/Jano-Projects/calculadora-rtc-facil/verificacao.yml?style=flat-square&label=testes)](https://github.com/Jano-Projects/calculadora-rtc-facil/actions)

| Repositório | Conteúdo | Atividade |
|---|---|---|
| [**calculadora-rtc-facil**](https://github.com/Jano-Projects/calculadora-rtc-facil) | Inicializador para Windows e Linux, atualização automática do motor oficial e tela de cálculo. | ![Último commit](https://img.shields.io/github/last-commit/Jano-Projects/calculadora-rtc-facil?style=flat-square&label=atualizado) |

**O que dá para fazer:**
- montar uma nota item a item, com autocompletar de NCM e sugestão da classificação tributária;
- comparar a mesma nota em duas datas (2026 × 2027) e ver a carga de hoje ao lado da de depois da reforma, inclusive no Simples Nacional (dentro ou fora do DAS);
- conferir o XML de uma NF-e ou NFC-e contra a calculadora oficial, item por item, para homologar sistemas emissores;
- compartilhar a nota por link e exportar para PDF, planilha ou JSON.

---

## Observatório de Pontualidade Aérea

Análise aberta da pontualidade das companhias aéreas no Brasil, construída sobre os dados oficiais da ANAC (Voo Regular Ativo). Os arquivos mensais são carregados, validados e organizados em um **modelo dimensional no Oracle**, com toda a regra de negócio em **PL/SQL testado com utPLSQL**. Uma aplicação web em **Oracle APEX** e uma **API REST (ORDS)** mostram os indicadores por mês, companhia, aeroporto, hora e dia da semana.

![Oracle](https://img.shields.io/badge/Oracle%20AI%20Database-26ai-F80000?style=flat-square&logo=oracle&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-utPLSQL-F80000?style=flat-square)
![APEX](https://img.shields.io/badge/Oracle%20APEX-24.2-C74634?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Dados](https://img.shields.io/badge/dados-ANAC%20(abertos)-0B4F8A?style=flat-square)

| Repositório | Conteúdo | Atividade |
|---|---|---|
| [**aviation-otp-observatory**](https://github.com/Jano-Projects/aviation-otp-observatory) | Banco Oracle em Docker, carga validada dos arquivos da ANAC, *star schema* e testes utPLSQL. | ![Último commit](https://img.shields.io/github/last-commit/Jano-Projects/aviation-otp-observatory?style=flat-square&label=atualizado) |
| [**aviation-otp-apex**](https://github.com/Jano-Projects/aviation-otp-apex) | Aplicação web em Oracle APEX e API REST em ORDS sobre o observatório. | ![Último commit](https://img.shields.io/github/last-commit/Jano-Projects/aviation-otp-apex?style=flat-square&label=atualizado) |

De janeiro a julho de 2026: **591.381 voos** carregados, nenhum rejeitado pela validação, com pontualidade mensal entre 80,7% e 85,3% (chegada até 15 minutos após o horário). Documentação em inglês, com guias de instalação em português.

---

## HONK!

**Um ganso acordou com ódio.** Roguelite em terceira pessoa, no estilo da xilogravura de cordel, em que o **motor do jogo é um banco de dados**: movimento, colisão, inteligência dos inimigos (busca em largura com CTE recursiva), combate, ondas, ciclos e cartas são **SQL**, rodando no DuckDB dentro do navegador. O JavaScript só lê o teclado e desenha a tela.

O jogo não tem fim: são cinco mundos por ciclo (Parque, Fazenda, Feira, Shopping e Aeroporto), e a cada volta os inimigos crescem conforme a força do próprio ganso. Os instaladores trazem o motor embutido, funcionam offline e abrem o jogo direto pelo ícone, sem terminal.

![SQL](https://img.shields.io/badge/SQL-DuckDB--WASM-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Gênero](https://img.shields.io/badge/gênero-roguelite-B8322A?style=flat-square)
![Licença](https://img.shields.io/badge/licença-GPL--3.0-B8322A?style=flat-square)
[![Versão](https://img.shields.io/github/v/release/Jano-Projects/honk?style=flat-square&label=versão&color=B8322A)](https://github.com/Jano-Projects/honk/releases/latest)
[![Testes](https://img.shields.io/github/actions/workflow/status/Jano-Projects/honk/testes.yml?style=flat-square&label=testes)](https://github.com/Jano-Projects/honk/actions)
[![Downloads](https://img.shields.io/github/downloads/Jano-Projects/honk/total?style=flat-square&label=downloads&color=1C2B33)](https://github.com/Jano-Projects/honk/releases)

| Repositório | Conteúdo | Atividade |
|---|---|---|
| [**honk**](https://github.com/Jano-Projects/honk) | Regras do jogo em SQL separadas por assunto, renderização em JavaScript, testes das regras e instaladores para Windows, Debian/Ubuntu, Fedora e macOS. | ![Último commit](https://img.shields.io/github/last-commit/Jano-Projects/honk?style=flat-square&label=atualizado) |

**[⬇ Baixar o HONK!](https://github.com/Jano-Projects/honk/releases/latest)**: instaladores para Windows (`.exe`), Debian/Ubuntu (`.deb`), Fedora (`.rpm`) e macOS (`.dmg`), além da versão portátil (`.zip`), cada um homologado automaticamente nas cinco plataformas antes de ser publicado.

---

## Plataformas

| Sistema | Aprendiz | Calculadora RTC Fácil | Observatório (Docker) | HONK! |
|---|:---:|:---:|:---:|:---:|
| Windows 10/11 | ✅ | ✅ | com Docker Desktop | ✅ |
| Fedora (versão atual) | ✅ | ✅ | ✅ | ✅ |
| Ubuntu (versão atual) | ✅ | ✅ | ✅ | ✅ |
| Debian (estável) | ✅ | ✅ | ✅ | ✅ |
| macOS | — | — | — | ✅ |

---

## Autoria e identidades nos repositórios

Todos os projetos deste perfil são criados e mantidos por uma única pessoa. Nos históricos de commits, o mesmo autor aparece com nomes diferentes, conforme a máquina ou a ferramenta usada para publicar:

| Identidade | Onde aparece | Quem é |
|---|---|---|
| **Victor H. Correa** | aprendiz-dev, aprendiz-addons, aviation-otp-observatory, aviation-otp-apex, honk | Eu. É o nome usado nos commits feitos das minhas máquinas de desenvolvimento. |
| **Victor Hugo dos Santos Correa** | README e licença dos projetos de aviação e do HONK! | Eu, com o nome completo, como autor e titular dos direitos. |
| **Jano-Projects** | calculadora-rtc-facil | Eu, com o nome da conta da organização. |
| **Projeto Jano** | este perfil, aprendiz-dev, aprendiz-addons | Eu, em edições feitas direto pelo site do GitHub. |
| **GitHub** | commits feitos pelo site | Assinatura automática da plataforma nas edições feitas pelo navegador. Não é outra pessoa. |
| **dependabot[bot]** | atualizações de dependências | Robô do GitHub que propõe atualizações de bibliotecas e de *actions*. Elas só entram depois que os testes automáticos passam. |

**Uso de inteligência artificial.** Utilizo o **Claude**, assistente de IA da Anthropic, no desenvolvimento: para refatorar código e para revisar e avaliar a documentação. O Claude não é autor de commits em nenhum repositório. Todo o código e a documentação são revisados, testados e publicados por mim.

---

## Princípios

1. **Local primeiro**: o processamento acontece na máquina do usuário e os dados não saem dela.
2. **Transparência**: código legível, comentado e documentado, e autoria declarada, inclusive o uso de IA.
3. **Qualidade verificável**: testes automáticos a cada alteração, com o resultado visível nos selos de cada repositório.
4. **Acesso livre**: uso, estudo e modificação gratuitos, sob licença MIT (no HONK!, GPL-3.0).

---

<div align="center">
<sub>© Projeto Jano · Victor H. Correa</sub>
</div>
