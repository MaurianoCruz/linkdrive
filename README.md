# LinkDrive

Protótipo navegável de uma plataforma de propostas para viagens agendadas de ida e volta em grupo.

## Demonstração

https://linkdrive-prototipo.maurianocruz.chatgpt.site (acesso privado)

## Funcionalidades

- Pedido de viagem com percurso, datas, horários e quantidade de passageiros.
- Escolha entre motorista à disposição durante o evento ou retorno agendado.
- Orçamento sugerido e comparação de propostas fictícias.
- Revisão das condições e confirmação de reserva simulada.
- Área do motorista para simular envio de proposta.
- Interface em português, adaptada para celular.

## Executar localmente

Requisito: Node.js 22.13 ou superior e npm.

```sh
npm ci
npm run dev
```

Abra o endereço local informado no terminal.

```sh
npm run build
npx tsc --noEmit
npx oxlint app
```

O lint geral também analisa os componentes do scaffold, que apresentam apontamentos preexistentes.

## Tecnologia

React, TypeScript, Vinext/Vite, Tailwind CSS, componentes Shadcn/Base UI e integração Sites/Cloudflare Workers. A configuração de hospedagem está em `.openai/hosting.json`.

## Limites do protótipo

Todos os motoristas, preços e reservas são demonstrativos. Não há pagamentos, autenticação própria, chat, validação documental ou armazenamento persistente. Recarregar a página reinicia a simulação. Não utilizar esta versão para contratar viagens reais.

## Próximos passos

Validar demanda com passageiros e motoristas; definir a operação e os requisitos locais; implementar cadastro e persistência; testar pagamentos e atendimento. Projeções de receita, custos e margem devem explicitar suas hipóteses e não representam resultados garantidos.
