Detector de Alucinações
O Detector de Alucinações é uma ferramenta gratuita e de código aberto que ajuda a verificar a precisão do seu conteúdo instantaneamente. Pense nele como o Grammarly, mas para precisão factual
em vez de gramática. Ele analisa seu conteúdo, identifica possíveis imprecisões e sugere correções apoiadas em fontes confiáveis da web.

✨ Principais Recursos

Verificação de fatos em tempo real do conteúdo gerado por LLM
Verificação baseada em fonte
Explicações detalhadas para imprecisões identificadas
Correções baseadas em sugestões

🛠️ Como funciona

Extração de Reivindicações: Quando você insere seu conteúdo, a ferramenta usa um LLM (Claude 3.5 Sonnet) para dividir seu texto em afirmações individuais.
Verificação de Fonte: Cada afirmação é verificada usando a ferramenta de busca do Exa para encontrar fontes online confiáveis que a apoiem ou refutem.
Análise de Precisão: As afirmações e suas fontes correspondentes são analisadas por nosso LLM para determinar sua precisão.
Exibição de Resultados: Por fim, mostramos os resultados de uma forma simples e clara, apontando quaisquer erros e oferecendo sugestões para corrigi-los.

💻 Pilha Tecnológica

Motor de Busca: Exa.ai - API de pesquisa avançada na web para aplicativos de IA
Frontend: Next.js com App Router, TailwindCSS, TypeScript
LLM: Anthropic's Claude 3.5 Sonnet - mas você pode usar qualquer LLM (ex: gpt, gemini, llama ou outros)
Integração de IA: Vercel AI SDK
Hospedagem: Vercel para hospedagem e análise

🚀 Primeiros passos

Pré-requisitos

Node.js
Chaves de API para Exa.ai e Anthropic
Instalação

Clone o repositório
Bash

git clone https://github.com/guilaweb/hallucination.git
cd exa-hallucination-detector
Instale as dependências
Bash

npm install
# ou
yarn install
Configure as variáveis de ambiente Crie um arquivo .env.local no diretório raiz e adicione suas chaves de API:
EXA_API_KEY=sua_chave_de_api_exa
ANTHROPIC_API_KEY=sua_chave_de_api_anthropic
Execute o servidor de desenvolvimento
Bash

npm run dev
# ou
yarn dev
Abra http://localhost:3000/hallucination-detector no seu navegador
🔑 Chaves de API

Obtenha sua chave de API Exa no Painel Exa
Obtenha sua chave de API Anthropic na Documentação Anthropic
⭐ Sobre a Exa.ai

Desenvolvido pelo Laboratório Guilaweb, o Detector de Alucinações é uma ferramenta gratuita e de código aberto que ajuda a verificar a precisão do seu conteúdo instantaneamente. Pense nele 
como o Grammarly, mas para precisão factual em vez de gramática. Ele analisa seu conteúdo, identifica possíveis imprecisões e sugere correções apoiadas em fontes confiáveis da web.
Este projeto é powered by Exa.ai, um mecanismo de pesquisa de ponta projetado especificamente para aplicativos de IA. O Exa fornece:

Recursos avançados de pesquisa semântica e baseada em palavras-chave
Recuperação instantânea de conteúdo limpo da web
Parâmetros de pesquisa personalizáveis
Pesquisa de similaridade usando URLs ou texto
Recursos de pesquisa superiores em comparação com APIs de pesquisa tradicionais
