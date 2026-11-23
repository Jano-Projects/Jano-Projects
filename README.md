<div align="center">

# Projeto Jano

**Software livre, local e documentado em português.**

Ferramentas que rodam no seu computador, com código aberto para usar, estudar e modificar.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-victor--hsc-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-hsc)
![Idioma](https://img.shields.io/badge/idioma-português-2E7D32?style=flat-square)
![Uso](https://img.shields.io/badge/uso-gratuito-555555?style=flat-square)
![Código](https://img.shields.io/badge/código-aberto-37474F?style=flat-square)

</div>

---

## Projetos

| | Projeto | Para quem | O que faz |
|---|---|---|---|
| 🧠 | [**Aprendiz**](#aprendiz) | Estudantes e devs de IA | Assistente pessoal offline que responde só com o que você ensina a ele. |
| 🧾 | [**Calculadora RTC Fácil**](#calculadora-rtc-fácil) | Empresas, contadores e equipes de ERP | Calcula CBS, IBS e Imposto Seletivo da Reforma Tributária com a calculadora oficial da Receita Federal, numa tela simples. |

---

## Aprendiz

Assistente pessoal **local e offline**. Responde exclusivamente com base no conhecimento fornecido pelo próprio usuário: não coleta dados, não acessa a internet e funciona inclusive em máquinas com poucos recursos. Todo o código é comentado em português, para servir também como material de estudo de Processamento de Linguagem Natural.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Offline](https://img.shields.io/badge/execução-100%25%20offline-37474F?style=flat-square)
![PLN](https://img.shields.io/badge/área-PLN-6A1B9A?style=flat-square)

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

</details>

---

## Calculadora RTC Fácil

Interface amigável para a [calculadora oficial da Reforma Tributária do Consumo](https://github.com/ReceitaFederal/calculadora-rtc-regime-regular) (LC 214/2025), da Receita Federal. Abre com **um clique**, sem instalar Java, Git ou qualquer outra coisa antes, e **se atualiza sozinha**: quando a Receita publica uma versão nova, ela é baixada, compilada e colocada em uso sem interromper quem está usando. Os cálculos rodam no próprio computador.

![Java](https://img.shields.io/badge/Java%2025-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Área](https://img.shields.io/badge/área-tributário-0E6B5A?style=flat-square)
[![Verificação](https://img.shields.io/github/actions/workflow/status/Jano-Projects/calculadora-rtc-facil/verificacao.yml?style=flat-square&label=testes)](https://github.com/Jano-Projects/calculadora-rtc-facil/actions)

| Repositório | Conteúdo | Atividade |
|---|---|---|
| [**calculadora-rtc-facil**](https://github.com/Jano-Projects/calculadora-rtc-facil) | Inicializador para Windows e Linux, atualização automática do motor oficial e tela de cálculo. | ![Último commit](https://img.shields.io/github/last-commit/Jano-Projects/calculadora-rtc-facil?style=flat-square&label=atualizado) |

**O que dá para fazer:** montar uma nota item a item (com autocompletar de NCM e as classificações tributárias vigentes), ver o resultado em forma de cupom com a memória de cálculo oficial, comparar a mesma nota em duas datas (2026 × 2027, por exemplo) e exportar para planilha ou JSON.

---

## Plataformas

| Sistema | Aprendiz | Calculadora RTC Fácil |
|---|:---:|:---:|
| Windows 10/11 | ✅ | ✅ |
| Fedora (versão atual) | ✅ | ✅ |
| Ubuntu (versão atual) | ✅ | ✅ |
| Debian (estável) | — | ✅ |

---

## Princípios

1. **Local primeiro**: o processamento acontece na máquina do usuário e os dados não saem dela.
2. **Transparência**: código legível, comentado e documentado em português.
3. **Acesso livre**: uso, estudo e modificação gratuitos.

---

<div align="center">
<sub>© Projeto Jano · Victor H. Correa</sub>
</div>
