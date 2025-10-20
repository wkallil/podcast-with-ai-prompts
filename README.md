# 🎙️ Marketing Sem Mistério: Podcast Gerado por IA

Este repositório documenta o processo de criação do podcast **"Marketing Sem Mistério"**, um projeto que utilizou **engenharia de prompts** e ferramentas de **Inteligência Artificial de Text-to-Speech (TTS)** para gerar conteúdo de marketing digital focado em iniciantes.

O objetivo foi simular e automatizar as etapas de concepção (nome e logo) e roteirização (conteúdo do episódio) do podcast.

## 🚀 Tecnologias e Responsabilidades

O projeto simulou a criação de um podcast usando três ferramentas de IA, cada uma com um papel definido:

| Tecnologia | Responsabilidade | Finalidade no Projeto |
| :--- | :--- | :--- |
| **Gemini** | Geração de Nomes | Criou sugestões iniciais para o nome do podcast (Script do Nome). |
| **ChatGPT** | Roteirização e Design | Gerou o script de design da logo e o roteiro completo do episódio (Scripts da Logo e do Podcast). |
| **ElevenLabs** | Text-to-Speech (TTS) | Ferramenta que seria utilizada para transformar o roteiro final em áudio de alta qualidade. |

## 🎯 Sobre o Podcast (O Conceito Original)

O "Marketing Sem Mistério" é um podcast de formato curto e explicativo. Seu propósito é descomplicar conceitos de marketing digital, tornando-os acessíveis para o público **iniciante**, sem o uso de jargões técnicos avançados.

---

## 💻 Etapas de Criação (Prompts e Geração)

As seguintes etapas foram guiadas por prompts (instruções textuais) para simular o processo criativo.

### 1. Nome e Conceito

O primeiro prompt focou na geração de nomes curtos e explicativos para iniciantes.

```text
Crie pelo menos 5 nomes para um podcast sobre marketing digital seguindo as diretrizes abaixo:
- os nomes devem ser curtos
- o podcast será explicativo
- o público-alvo são iniciantes no marketing digital
- os nomes não devem ter quaisquer palavras próximas a "educação"
```

***Nome Escolhido: Marketing Sem Mistério***

### 2. Identidade Visual (Logo)

Um prompt específico foi usado para gerar a identidade visual do podcast, que seria a capa de um episódio ou perfil.

```text
Faça um logo para um podcast de marketing digital. O nome do podcast é "Marketing Sem mistério".

- Faça um imagem sem muitas informações
- Imagem não realista
- Design limpo e simples
- Azul e Amarelo são as cores principais
- Imagem quadriculada
```

![Logo do Podcast Marketing Sem Mistério (Gerada por Prompt)](https://ibb.co/3YCNVL5m)

### 3. Roteiro e Conteúdo (Base para Text-to-Speech)

O prompt mais detalhado foi usado para criar o roteiro do primeiro episódio, seguindo uma estrutura rígida e regras de tom de voz.
```text
**Regras do Prompt para Roteiro:**
Você é um roteirista de podcast, e vamos criar um  roteiro de um podcast de marketing digital, focado em ensinar de forma simples conceitos de marketing digital cujo o nome é "Marketing Sem mistério" e tem foco em diferentes modelos de marketing digital, com o público alvo de iniciantes em marketing digital

o formato do roteiro deve ser
[INTRODUÇÃO]
[PONTO 1]
[PONTO 2]
[PONTO 3]
[FINALIZAÇÃO]

{REGRAS}
- no bloco [INTRODUÇÃO] substitua por uma introdução iguais as introduções dos vídeos de canais famosos do youtube
- no bloco [PONTO 1] substitua por um breve início do que é marketing digital de afiliados
- no bloco [PONTO 3] susbtitua por uma explicação mais aprofundada do marketing digital de afiliados
- no bloco [PONTO 2] susbtitua por diferenças do marketing digital de afiliados para outros modelos de marketing digital existente e pq utilizar
- no bloco [FINALIZAÇÃO] substitua por uma despedida cool com o final 'Nós somos o Marketing Sem Mistério e estamos aqui para descomplicar o Marketing Digital, até o próximo episódio'
- use termos de fácil explicação
- O podcast vai ser apresentado somente por uma pessoa
- O podcast deve ser curto

{REGRAS NEGATIVAS}
- Não use muitos termos técnicos avançados
- Não ultrapasse 5 minutos de duração
```

**Conteúdo do Roteiro Gerado:**

O texto a seguir serve como o *input* para qualquer ferramenta de **Text-to-Speech (TTS)**, transformando o roteiro em áudio com voz de IA.

```text
[Transcrição do Episódio: Marketing de Afiliados]

"E aí, pessoal! Seja muito bem-vindo ao Marketing Sem Mistério!
Aqui a gente fala de marketing digital de um jeito simples, direto e sem enrolação.
Se você está começando agora e quer entender como o marketing digital realmente funciona, esse é o seu lugar!
No episódio de hoje, a gente vai falar sobre um dos modelos mais populares e acessíveis do mundo digital: o marketing de afiliados. Então, prepara o café e vem comigo!"

"Pra começar do básico: o marketing de afiliados é um modelo em que você divulga produtos ou serviços de outras pessoas ou empresas, e ganha uma comissão toda vez que alguém compra através do seu link.

É como se você fosse um vendedor digital, mas sem precisar criar o produto, cuidar de estoque ou atendimento ao cliente.
Seu papel é apenas indicar algo que realmente ajude o público e, em troca, você ganha uma parte das vendas.

Simples assim!"

"Mas talvez você esteja pensando: ‘Tá, e qual a diferença disso pra outros tipos de marketing digital?’
Boa pergunta!

No marketing de afiliados, o foco está em indicar produtos prontos, enquanto em outros modelos — como o infoprodutor, o e-commerce ou o freelancer digital — você é quem cria, vende ou entrega o produto ou serviço.

O afiliado, por outro lado, pode começar com baixo investimento, trabalhar de qualquer lugar e aprender na prática como funciona o mundo das vendas online.
É um ótimo ponto de partida pra quem quer entrar no marketing digital sem complicação.”

“Agora, pra entender um pouco mais: o segredo do marketing de afiliados não está só em compartilhar links, mas em gerar valor.

Isso significa escolher um nicho que você realmente conhece, entender as dores das pessoas e recomendar soluções que façam sentido pra elas.
Pode ser através de um Instagram temático, um canal no YouTube, blog ou até anúncios pagos — o importante é criar confiança.

Quanto mais as pessoas confiam em você, mais chances têm de comprar pelo seu link.
E é aí que o afiliado deixa de ser apenas um divulgador e se torna um influenciador de decisões.”

“E aí, curtiu entender um pouco mais sobre o marketing de afiliados?
No próximo episódio, a gente vai continuar descomplicando o marketing digital e mostrando como você pode dar os primeiros passos nesse universo.

Nós somos o Marketing Sem Mistério e estamos aqui para descomplicar o Marketing Digital.
Até o próximo episódio!”
```
