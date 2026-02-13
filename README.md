🚀 Modos do Copiloto
Ask · Edit · Plan · Agent · Study

O Copiloto oferece diferentes modos de trabalho para você escolher como quer interagir em cada momento.

A ideia é simples:
você decide o nível de controle e profundidade — desde tirar uma dúvida rápida sem tocar no código, até delegar uma implementação completa com padrão de engenharia.

Cada modo tem um propósito claro.

❓ Ask (Perguntar)
O modo Ask é para entender.

Aqui você faz perguntas sobre:

arquivos específicos

funções

stack traces

erros

decisões de arquitetura

conceitos técnicos

O Copiloto analisa o contexto e responde como um mentor técnico.
Ele explica o que está acontecendo, aponta hipóteses e sugere caminhos — mas não altera nada no código.

É o modo ideal quando você quer clareza antes de agir.

📄 Prompt: prompts/prompt-ask.md

✏️ Edit (Editar)
O modo Edit é para modificar código existente.

Você seleciona um trecho ou arquivo e descreve o que deseja mudar.
O Copiloto transforma o que já existe, mantendo o padrão do projeto.

Ideal para:

refatorações

reorganização de lógica

melhoria de desempenho

ajustes de estilo

conversão de padrões

adicionar logs

tratar erros

Aqui o foco é direto:
“Pegue isso e transforme.”

📄 Prompt: prompts/prompt-edit.md

🧭 Plan (Planejar)
O modo Plan é para mudanças maiores ou decisões estruturais.

Antes de escrever código, o Copiloto:

divide o problema em etapas

descreve arquivos afetados

define critérios de aceite

aponta riscos

sugere estratégia de testes

Só depois, se você aprovar, parte para a implementação.

É o modo ideal quando:

o impacto é grande

envolve múltiplos arquivos

você quer validar a abordagem antes de mexer no projeto

Planejar antes de agir evita retrabalho.

📄 Prompt: prompts/prompt-plan.md

🤖 Agent (Agente)
O modo Agent é o mais completo e autônomo.

Você define um objetivo claro, por exemplo:

“Implementar login com JWT.”

E o Copiloto:

navega pela estrutura do projeto

cria ou modifica múltiplos arquivos

mantém consistência com a stack

entrega código pronto para executar

Ele trabalha como um desenvolvedor júnior orientado, mas com padrão de engenharia:
organização, tratamento de erros, validação e testes quando necessário.

Esse modo é indicado para:

novas funcionalidades

integrações completas

automações

tarefas maiores e mais técnicas

📄 Prompt: prompts/prompt-agent.md

📚 Study (Estudar)
O modo Study é focado em aprendizado real.

Aqui o objetivo não é só resolver — é entender.

Ele:

explica conceitos com progressão (básico → avançado)

destaca trade-offs

usa analogias quando necessário

mostra exemplos práticos

faz perguntas para validar compreensão

Funciona como um tutor técnico particular.
Ideal quando você quer dominar o assunto, não apenas aplicar uma solução.

📄 Prompt: prompts/prompt-study.md

🧠 Resumo Mental Rápido
Ask → entender antes de agir

Edit → modificar código existente

Plan → organizar antes de implementar

Agent → executar tarefa completa

Study → aprender com profundidade
