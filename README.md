# Explicador de Hemograma

Ferramenta web gratuita que ajuda pessoas a entenderem o resultado do hemograma: a pessoa digita os valores do exame e vê o que cada item significa e se está dentro da faixa de referência para adultos.

**Importante:** é uma ferramenta informativa. Não faz diagnóstico e não substitui a avaliação médica.

## Recursos

- 11 itens do hemograma: hemoglobina, hematócrito, hemácias, VCM, HCM, CHCM, RDW, leucócitos, neutrófilos, linfócitos e plaquetas
- Faixas de referência para adultos, com ajuste por sexo biológico onde se aplica
- Explicação em linguagem simples do que cada item representa e do que valores fora da faixa podem indicar
- Alerta para valores muito distantes da faixa, orientando a procurar atendimento
- Detecção de unidade digitada errada (por exemplo, plaquetas "250" em vez de "250000")
- Funciona no celular e no computador
- Privacidade: todo o cálculo acontece no navegador, nenhum dado é enviado ou guardado
- Um único arquivo (`index.html`), sem dependências nem instalação

## Como usar

Abra o `index.html` no navegador, ou acesse a versão publicada pelo GitHub Pages.

## Limitações

- Faixas de referência variam entre laboratórios; na dúvida, use a faixa impressa no laudo
- Não considera gestantes, crianças e idosos
- Não inclui eosinófilos, monócitos e basófilos

## Tecnologias

HTML, CSS e JavaScript puro.

## Próximos passos (ideias)

- Faixas por idade e para gestantes
- Campo para o usuário informar a faixa do próprio laudo
- Itens adicionais do hemograma (eosinófilos, monócitos, basófilos)
- Versão em inglês
