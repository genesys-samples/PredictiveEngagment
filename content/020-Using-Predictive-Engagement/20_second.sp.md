---
title: "Segmentos, Resultados (Outcomes), y Mapas de Acción (Action Maps)"
chapter: false
weight: 20
---

### Segmentos
#### Definición:
Grupo de visitantes que comparten un comportamiento o características similares. Los segmentos de sesión caducan cuando finaliza la sesión individual. Los segmentos de clientes persisten entre sesiones. Para obtener más información, consulte **[Crear segmentos](https://all.docs.genesys.com/ATC/Current/AdminGuide/Manage_segments)**.
#### Qué significa esto:
Los segmentos se utilizan para identificar a los visitantes en función de sus características comunes. Posteriormente, se diseñan mapas de acción para captar segmentos específicos de visitantes y luego se filtra por segmentos para evaluar lo bien que se les está captando. 
Algunos ejemplos de segmentos son: 
- Atributos de los visitantes
    - Localización 
    - Tipo de navegador 
    - Tipo de dispositivo y sistema operativo
- Trayectoria del visitante
    - URL de la página
    - Consulta de búsqueda 
    - Búsqueda por palabra clave
![Segmento](/images/SegmentConfig.png)
### Resultados - Outcomes
#### Definición:
Objetivo empresarial que desea seguir y alcanzar. Para obtener más información, consulte **[Crear resultados](https://all.docs.genesys.com/ATC/Current/AdminGuide/Manage_outcomes)**.
#### Qué significa esto:
Genesys Predictive Engagement utiliza el aprendizaje automático basado en IA para predecir la probabilidad de que los visitantes alcancen sus resultados empresariales exclusivos.   
Algunos ejemplos de condiciones y características rastreables
- Tiempo de inactividad
- Abandono de formulario
- Envío
- Página visitada
![Outcomes](/images/OutcomeConfig.png)
### Mapas de Acción - Action Maps
#### Definición:
Define cómo desea que Genesys Predictive Engagement interactúe con un visitante en función de los segmentos coincidentes del visitante y de sus resultados preferidos. Para obtener más información, consulte **[Crear un mapa de acción](https://all.docs.genesys.com/ATC/Current/AdminGuide/Action_maps)**.
#### Qué significa esto:
Los mapas de acción utilizan diferentes tipos de acciones para mejorar y ampliar el recorrido de un visitante. 
Algunas acciones que pueden activarse en función de los segmentos de visitantes: 
- Ofrecer Chat Web o Mensaje Web
- Oferta Content Pop
    - Código de descuento
    - Ofertas especiales
- Orquestación Avanzada (Flujo de Architect a consultas, bots, o para actualizar un sistema de terceros)
![ActionMap](/images/ActionMapConfig.png)