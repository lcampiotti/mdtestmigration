    Tutoriales — Qflow Cloud          

*   [Qflow](https://qflowbpm.com/es/)
*   [Foro](https://forum.qflowbpm.com/)
*   [Centro de Ayuda](https://qflowbpm.com/es/centro-de-ayuda/)
*   [Contáctanos](https://qflowbpm.com/es/contacto/)

[Qflow](index.html)

Cloud (latest) 5.5 OnPremise (latest) 5.2 OnPremise 5.1.1 OnPremise

English Español

selectElement('versionSelect', getVersion()); selectElement('languageSelect', getLanguage()); function selectElement(id, valueToSelect) { let element = document.getElementById(id); element.value = valueToSelect; } function getLanguage() { if (window.location.href.includes('/es/')) { return '/es/'; } else { return '/en/'; } } function getVersion() { if (window.location.href.includes('/qflowcloud/')) { return '/qflowcloud/'; } else if (window.location.href.includes('/qflow5\_1\_1/')) { return '/qflow5\_1\_1/'; } else if (window.location.href.includes('/qflow5\_2/')) { return '/qflow5\_2/'; } else { return '/qflow5\_5/'; } } function redirectToSite(url) { var http = new XMLHttpRequest(); http.onreadystatechange = function() { if (http.readyState === 4) { if (http.status !== 404) { window.location.href = url; } else { window.location.href = url.replace(url.substr(url.lastIndexOf('/') + 1), 'index.html'); } } } http.open('HEAD', url, true); http.send(); }

  

Inicio

*   [Novedades](29-ReleaseNote.html)
*   [Introducción a Qflow](01-QflowIntroduction.html)
*   [Tutoriales](#)
    *   [Introducción a las herramientas de Qflow](26-QflowToolsTutorial.html)
    *   [Crea tu primer proceso](06-Tutorial.html)
    *   [Diseña un proceso de quejas](23-DesignTutorial.html)
    *   [Descubre Qflow Task](24-QflowTaskTutorial.html)
    *   [Configura el equipo](27-QflowTeamTutorial.html)
    *   [Administra y monitorea el sistema](28-QflowAdminTutorial.html)
    *   [Crea tu formulario personalizado](37-QformTutorial.html)
*   [Qflow Task](04-QflowTask.html)
*   [Qflow Design](15-QflowDesign.html)
*   [Qflow Team](18-QflowTeam.html)
*   [Qflow Admin](19-QflowAdmin.html)
*   [Consumo de Q-points](21-Q-pointsConsumption.html)
*   [Conectores](34-ConnectorsIndex.html)
*   [Desarrolladores](31-Development.html)

[Qflow](index.html)

*   [](index.html)
*   Tutoriales

- - -

# Tutoriales[](#tutoriales "Link to this heading")

Inicio

*   [Introducción a las herramientas de Qflow](26-QflowToolsTutorial.html)
    *   [Introducción](26-QflowToolsTutorial.html#introduccion)
    *   [Qflow Design: diseñador web de procesos de negocio](26-QflowToolsTutorial.html#qflow-design-disenador-web-de-procesos-de-negocio)
    *   [Qflow Task: herramienta de tareas y procesos](26-QflowToolsTutorial.html#qflow-task-herramienta-de-tareas-y-procesos)
    *   [Qflow Team: administrador del equipo de trabajo y su estructura organizacional](26-QflowToolsTutorial.html#qflow-team-administrador-del-equipo-de-trabajo-y-su-estructura-organizacional)
    *   [Qflow Admin: administración y monitoreo del sistema](26-QflowToolsTutorial.html#qflow-admin-administracion-y-monitoreo-del-sistema)
*   [Crea tu primer proceso](06-Tutorial.html)
    *   [Objetivo](06-Tutorial.html#objetivo)
    *   [Descripción del proceso](06-Tutorial.html#descripcion-del-proceso)
    *   [Diseño del proceso](06-Tutorial.html#diseno-del-proceso)
    *   [Ejecución del proceso](06-Tutorial.html#ejecucion-del-proceso)
*   [Diseña un proceso de quejas](23-DesignTutorial.html)
    *   [Introducción](23-DesignTutorial.html#introduccion)
    *   [Proceso de quejas](23-DesignTutorial.html#proceso-de-quejas)
    *   [Construcción del proceso de Qflow](23-DesignTutorial.html#construccion-del-proceso-de-qflow)
*   [Descubre Qflow Task](24-QflowTaskTutorial.html)
    *   [Introducción](24-QflowTaskTutorial.html#introduccion)
    *   [Trabajo con procesos](24-QflowTaskTutorial.html#trabajo-con-procesos)
    *   [Herramientas de seguimiento y análisis de procesos](24-QflowTaskTutorial.html#herramientas-de-seguimiento-y-analisis-de-procesos)
*   [Configura el equipo](27-QflowTeamTutorial.html)
    *   [Introducción](27-QflowTeamTutorial.html#introduccion)
    *   [Estructura de nodos](27-QflowTeamTutorial.html#estructura-de-nodos)
    *   [Colas de trabajo](27-QflowTeamTutorial.html#colas-de-trabajo)
    *   [Administrar permisos de la herramienta](27-QflowTeamTutorial.html#administrar-permisos-de-la-herramienta)
*   [Administra y monitorea el sistema](28-QflowAdminTutorial.html)
    *   [Introducción](28-QflowAdminTutorial.html#introduccion)
    *   [Parámetros de sistema](28-QflowAdminTutorial.html#parametros-de-sistema)
    *   [Estadísticas](28-QflowAdminTutorial.html#estadisticas)
*   [Crea tu formulario personalizado](37-QformTutorial.html)
    *   [Contexto del proceso](37-QformTutorial.html#contexto-del-proceso)
    *   [Diseñar el formulario único con visibilidad por paso](37-QformTutorial.html#disenar-el-formulario-unico-con-visibilidad-por-paso)
    *   [Configurar visibilidad y comportamiento de campos](37-QformTutorial.html#configurar-visibilidad-y-comportamiento-de-campos)
    *   [Validar el diseño con vista previa](37-QformTutorial.html#validar-el-diseno-con-vista-previa)
    *   [Ejecutar una instancia de prueba](37-QformTutorial.html#ejecutar-una-instancia-de-prueba)
    *   [Resultado esperado](37-QformTutorial.html#resultado-esperado)

[Anterior](01-QflowIntroduction.html "Introducción a Qflow") [Siguiente](26-QflowToolsTutorial.html "Introducción a las herramientas de Qflow")

- - -

© Derechos de autor 2025, Urudata Software.

jQuery(function () { SphinxRtdTheme.Navigation.enable(true); }); window.dataLayer = window.dataLayer || \[\]; function gtag(){dataLayer.push(arguments);} gtag('js', new Date()); gtag('config', 'G-LMDS8S4B42', { 'anonymize\_ip': false, });
