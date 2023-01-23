---
title: "Segmentos, Resultados, e Mapas de Ação"
chapter: false
weight: 20
locale: "pt-BR"
---

### Segmentos
#### Definição:
Grupo de visitantes que compartilham comportamento ou características semelhantes. Os segmentos de sessão expiram quando a sessão única termina. Os segmentos de clientes persistem nas sessões. Para mais informações, veja **[Criar segmento](https://all.docs.genesys.com/ATC/Current/AdminGuide/Manage_segments)**.
#### O que isso significa:
Os segmentos são usados para identificar os visitantes com base em suas características compartilhadas. Mais tarde, você projeta mapas de ação para envolver segmentos específicos de visitantes e, em seguida, filtrar por segmentos para avaliar o quão bem você os está engajando.
Alguns exemplos de segmentos são: 
- Atributos do visitante
    - Localização 
    - Tipo de Browser (Navegador) 
    - Tipo de dispositivo e sistema operacional
- Jornada do Visitante
    - URL da Página
    - Consulta de pesquisa 
    - Pesquisa de palavras-chave
![Segmento](/images/SegmentConfig.png)
### Resultados
#### Definição:
Meta de negócios que você deseja acompanhar e alcançar. Para mais informações, consulte **[Criar Resultados](https://all.docs.genesys.com/ATC/Current/AdminGuide/Manage_outcomes)**.
#### O que isso significa:
Genesys Predictive Engagement usa o aprendizado de máquina com tecnologia de IA para prever a probabilidade de os visitantes alcançarem seus resultados de negócios exclusivos.   
Alguns exemplos de condições e características rastreáveis
- Tempo Ocioso
- Formulário de Abandono
- Envio
- Página visualizada
![Resultados](/images/OutcomeConfig.png)
### Mapas de Ação
#### Definição:
Define como você deseja que o Genesys Predictive Engagement interaja com um visitante com base nos segmentos correspondentes do visitante e em seus resultados preferidos. Para mais informações, veja **[Criar um Mapa de Ação](https://all.docs.genesys.com/ATC/Current/AdminGuide/Action_maps)**.
#### What this means:
Os mapas de ação usam diferentes tipos de ações para aprimorar e estender a jornada do visitante.
Algumas ações que podem ser acionadas com base nos segmentos de visitantes: 
- Ofertar Web Chat ou Web Message
- Ofertar Banner de Conteúdo Personalizado
    - Código (ou QR Code) de desconto
    - Ofertas Especiais
- Orquestração avançada (fluxo para consultas, bots ou para atualizar um sistema de terceiros usando o Genesys Architect)
![ActionMap](/images/ActionMapConfig.png)