# 🤖 Análise de Sentimentos com Language Studio (Microsoft Azure)

Este projeto foi desenvolvido como parte do **Desafio de Inteligência Artificial** do **Curso de Análise de Dados da Randstad – 2025**, com o objetivo de aplicar conceitos básicos de **Processamento de Linguagem Natural (NLP)** usando ferramentas online e gratuitas, sem necessidade de codificação.

## 🎯 Objetivo

Executar uma análise de sentimento de textos em português, classificando frases como **positivas**, **negativas** ou **neutras** por meio do **Microsoft Azure Language Studio**.

---

## 🛠 Ferramentas Utilizadas

- 🌐 [Microsoft Azure Language Studio](https://language.cognitive.azure.com/)
- 📂 [GitHub](https://github.com)
- ✍️ [Markdown Guide para GitHub](https://guides.github.com/features/mastering-markdown/)

---

## 🧪 Textos Utilizados para Análise

### Texto 01: *Futebol – Sport Club do Recife*
> O Sport Club do Recife, um gigante pernambucano, sempre se destaca pela sua paixão e garra em campo, com uma torcida vibrante que empurra o time a cada jogo. O acesso recente à Série A demonstra a força do elenco e a capacidade de superação. Contudo, a equipe precisa melhorar a consistência defensiva e a criação de jogadas no meio-campo. A dependência de alguns jogadores chave pode ser um ponto fraco em caso de desfalques. O desafio agora é manter a estabilidade para consolidar-se na elite do futebol brasileiro.

### Texto 02: *Política – Análise dos ex-presidentes*
> Luiz Inácio Lula da Silva, em seus mandatos anteriores, é frequentemente elogiado por programas sociais como o Bolsa Família, que tiraram milhões da pobreza, e por um período de crescimento econômico com inclusão social. Seus críticos, no entanto, apontam para os escândalos de corrupção que ocorreram durante seu governo, como o Mensalão e a Lava Jato, que geraram grande desgaste institucional e questionamentos sobre a ética na política.  
>  
> Jair Messias Bolsonaro, por sua vez, é visto por seus apoiadores como um defensor da liberdade individual, da pauta conservadora e da redução da burocracia, além de ter buscado uma agenda econômica liberal. Por outro lado, seus detratores criticam sua gestão da pandemia de COVID-19, o desmonte de órgãos de fiscalização ambiental e a retórica polarizadora, que, segundo eles, minou a democracia e a harmonia social.

---

## 🔍 Resultados da Análise

Os resultados das análises completas — tanto finais quanto por sentença — estão disponíveis na pasta `/images`. Foram analisadas as emoções predominantes em cada trecho textual.

---

### 📂 Estrutura do Diretório
```text
├── README.md
├── index.html
├── textos-testados.txt     
└── images/
    ├── 01-resultado-final-texto-01.png
    ├── 01-resultado-sentença-01-texto-01.png
    ├── 01-resultado-sentença-02-texto-01.png
    ├── 01-resultado-sentença-03-texto-01.png
    ├── 01-resultado-sentença-04-texto-01.png
    ├── 01-resultado-sentença-05-texto-01.png
    ├── 02-resultado-final-texto-02.png
    ├── 02-resultado-sentença-01-texto-02.png
    ├── 02-resultado-sentença-02-texto-02.png
    ├── 02-resultado-sentença-03-texto-02.png
    └── 02-resultado-sentença-04-texto-02.png
```
---

## ⚙️ Passo a Passo – Executando no Azure Language Studio

### 1. Criar Conta (caso não tenha)

- Acesse o portal: [https://portal.azure.com](https://portal.azure.com)
- Use um e-mail pessoal. A ferramenta é gratuita para testes simples.

### 2. Acessar o Language Studio

- Vá para: [https://language.cognitive.azure.com/](https://language.cognitive.azure.com/)
- Clique em **"Analyze text"** no menu lateral.
- Escolha a opção **"Sentiment Analysis"**.

### 3. Inserir o Texto

- Copie um dos textos acima e cole na área de análise.
- Clique em **Run** para executar.
- O sistema retornará:
  - Sentimento geral do texto
  - Sentimento individual por sentença
  - Pontuações de confiança (confidence scores)

### 4. Salvar os Resultados

- Armazenamento das imagens na pasta `/images` do repositório

---

## 💬 Exemplos de Classificação

| Texto | Sentimento Predominante |
|-------|--------------------------|
| Sport Club do Recife | Misto (predominância neutra com trechos positivos e negativos) |
| Análise dos presidentes | Misto (polarização clara entre positivos e negativos) |

---

## 📚 Referências

- 🔗 [Azure Language Studio](https://language.cognitive.azure.com/)
- 📘 [Módulo oficial do Azure: Analyze text](https://learn.microsoft.com/training/modules/analyze-text-language-service/)
- 📘 [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)
- 📘 [Documentação GitHub (pt-BR)](https://docs.github.com/pt)

---
# 📊 Conclusões da Análise de Sentimentos com Microsoft Azure Language Studio

Este relatório apresenta os resultados obtidos com a ferramenta de **análise de sentimentos do Azure Language Studio**, aplicada a dois textos distintos em português. O objetivo foi avaliar a capacidade do modelo em identificar emoções e julgamentos implícitos, mesmo em textos mistos e com nuances.

---

## 🟥 Análise do Texto 01 – *Sport Club do Recife*

📄 **Resumo do texto**  
O texto apresenta o Sport como um clube tradicional e vibrante, exaltando a paixão da torcida e o recente acesso à Série A. Ao mesmo tempo, levanta críticas construtivas sobre problemas defensivos, dependência de jogadores-chave e a necessidade de estabilidade.

📊 **Resultado da IA**  
- **Sentimento Geral:** Misto (Mixed)  
- **Distribuição:**  
  - 🟩 Positivo: 26%  
  - 🟦 Neutro: 23%  
  - 🟥 Negativo: 51%  
- **Confiança:** 26%

✅ **Interpretação**  
Apesar do tom inicial positivo, as menções a falhas e riscos competitivos aumentaram o peso negativo no texto. A IA foi precisa ao considerar que há **uma dualidade emocional**: orgulho e preocupação.

---

## 🟦 Análise do Texto 02 – *Lula e Bolsonaro*

📄 **Resumo do texto**  
O texto descreve aspectos positivos e negativos dos governos de Luiz Inácio Lula da Silva e Jair Bolsonaro. Tenta apresentar uma visão equilibrada, abordando conquistas, críticas, escândalos e controvérsias associadas a ambos.

📊 **Resultado da IA**  
- **Sentimento Geral:** Negativo  
- **Distribuição:**  
  - 🟩 Positivo: 10%  
  - 🟦 Neutro: 7%  
  - 🟥 Negativo: 83%  
- **Confiança:** 100%

✅ **Interpretação**  
Mesmo sendo um texto com intenção analítica, a **carga emocional negativa** foi predominante — com termos fortes como “escândalos”, “corrupção”, “desmonte” e “minou a democracia”. A IA interpretou corretamente que o **tom geral do texto é crítico**, independentemente da tentativa de imparcialidade.

---

## ✅ Conclusão Geral

- A IA do **Azure Language Studio** foi eficaz em identificar sentimentos **em textos complexos e ambíguos**.
- O modelo demonstrou sensibilidade ao **contexto**, conseguindo detectar emoções positivas, neutras e negativas em conjunto.
- Mesmo quando a estrutura textual busca equilíbrio, o modelo identifica **o peso emocional dominante** com base no vocabulário e nas intenções latentes.

🎯 **Resumo:**  
> A análise de sentimentos baseada em IA não interpreta neutralidade política ou clubismo — ela mede a **intensidade emocional expressa no texto**. E neste projeto, ficou claro que a IA é capaz de reconhecer **polarizações, elogios e críticas com boa precisão**, mesmo em textos humanos e subjetivos.
---
✅ Este projeto validou a capacidade de uma solução **no-code** da Microsoft para aplicações reais em **Processamento de Linguagem Natural (NLP)**.
---

