    Bienvenido a la documentación de Qflow — Qflow Cloud         

*   [Qflow](https://qflowbpm.com/es/)
*   [Foro](https://forum.qflowbpm.com/)
*   [Centro de Ayuda](https://qflowbpm.com/es/centro-de-ayuda/)
*   [Contáctanos](https://qflowbpm.com/es/contacto/)

[Qflow](#)

Cloud (latest) 5.5 OnPremise (latest) 5.2 OnPremise 5.1.1 OnPremise

English Español

selectElement('versionSelect', getVersion()); selectElement('languageSelect', getLanguage()); function selectElement(id, valueToSelect) { let element = document.getElementById(id); element.value = valueToSelect; } function getLanguage() { if (window.location.href.includes('/es/')) { return '/es/'; } else { return '/en/'; } } function getVersion() { if (window.location.href.includes('/qflowcloud/')) { return '/qflowcloud/'; } else if (window.location.href.includes('/qflow5\_1\_1/')) { return '/qflow5\_1\_1/'; } else if (window.location.href.includes('/qflow5\_2/')) { return '/qflow5\_2/'; } else { return '/qflow5\_5/'; } } function redirectToSite(url) { var http = new XMLHttpRequest(); http.onreadystatechange = function() { if (http.readyState === 4) { if (http.status !== 404) { window.location.href = url; } else { window.location.href = url.replace(url.substr(url.lastIndexOf('/') + 1), 'index.html'); } } } http.open('HEAD', url, true); http.send(); }

  

Inicio

*   [Novedades](29-ReleaseNote.html)
*   [Introducción a Qflow](01-QflowIntroduction.html)
*   [Tutoriales](TutorialsIndex.html)
*   [Qflow Task](04-QflowTask.html)
*   [Qflow Design](15-QflowDesign.html)
*   [Qflow Team](18-QflowTeam.html)
*   [Qflow Admin](19-QflowAdmin.html)
*   [Consumo de Q-points](21-Q-pointsConsumption.html)
*   [Conectores](34-ConnectorsIndex.html)
*   [Desarrolladores](31-Development.html)

[Qflow](#)

*   [](#)
*   Bienvenido a la documentación de Qflow

- - -

# Bienvenido a la documentación de Qflow[](#bienvenido-a-la-documentacion-de-qflow "Link to this heading")

Inicio

*   [Novedades](29-ReleaseNote.html)
    *   [v6.0](29.13-ReleaseNote6_0.html)
    *   [v5.6.2](29.12-ReleaseNote5_6_2.html)
    *   [v5.6.1](29.11-ReleaseNote5_6_1.html)
    *   [v5.6](29.10-ReleaseNote5_6.html)
    *   [v5.5.4](29.9-ReleaseNote5_5_4.html)
    *   [v5.5.3](29.8-ReleaseNote5_5_3.html)
    *   [v5.5.1](29.7-ReleaseNote5_5_1.html)
    *   [v5.5](29.6-ReleaseNote5_5.html)
    *   [v5.4](29.5-ReleaseNote5_4.html)
    *   [v5.3](29.4-ReleaseNote5_3.html)
    *   [v5.2](29.3-ReleaseNote5_2.html)
    *   [v5.1.2](29.2-ReleaseNote5_1_2.html)
    *   [v5.1.1](29.1-ReleaseNote5_1_1.html)
    *   [v5.1](29.1-ReleaseNote5_1_Cloud.html)
*   [Introducción a Qflow](01-QflowIntroduction.html)
    *   [Introducción](01-QflowIntroduction.html#introduccion)
    *   [Organización de este manual](01-QflowIntroduction.html#organizacion-de-este-manual)
    *   [Qué es Qflow y para qué sirve](01-QflowIntroduction.html#que-es-qflow-y-para-que-sirve)
    *   [Qflow y la organización](01-QflowIntroduction.html#qflow-y-la-organizacion)
    *   [Componentes de Qflow](01-QflowIntroduction.html#componentes-de-qflow)
    *   [Guía de la documentación de Qflow](01-QflowIntroduction.html#guia-de-la-documentacion-de-qflow)
*   [Tutoriales](TutorialsIndex.html)
    *   [Introducción a las herramientas de Qflow](26-QflowToolsTutorial.html)
    *   [Crea tu primer proceso](06-Tutorial.html)
    *   [Diseña un proceso de quejas](23-DesignTutorial.html)
    *   [Descubre Qflow Task](24-QflowTaskTutorial.html)
    *   [Configura el equipo](27-QflowTeamTutorial.html)
    *   [Administra y monitorea el sistema](28-QflowAdminTutorial.html)
    *   [Crea tu formulario personalizado](37-QformTutorial.html)
*   [Qflow Task](04-QflowTask.html)
    *   [Introducción](04-QflowTask.html#introduccion)
    *   [Organización de este manual](04-QflowTask.html#organizacion-de-este-manual)
    *   [Descripción de Qflow Task](04-QflowTask.html#descripcion-de-qflow-task)
    *   [Trabajo con procesos y tareas](04-QflowTask.html#trabajo-con-procesos-y-tareas)
    *   [Herramientas de seguimiento y análisis de procesos](04-QflowTask.html#herramientas-de-seguimiento-y-analisis-de-procesos)
    *   [Administración y configuración](04-QflowTask.html#administracion-y-configuracion)
*   [Qflow Design](15-QflowDesign.html)
    *   [Introducción](15-QflowDesign.html#introduccion)
    *   [Organización de este manual](15-QflowDesign.html#organizacion-de-este-manual)
    *   [Guía rápida](15-QflowDesign.html#guia-rapida)
    *   [Operación de la interfaz de usuario](15-QflowDesign.html#operacion-de-la-interfaz-de-usuario)
    *   [Asistente de inteligencia artificial](15-QflowDesign.html#asistente-de-inteligencia-artificial)
    *   [Ítems del proceso](15-QflowDesign.html#items-del-proceso)
    *   [Elementos del diseño de un proceso](15-QflowDesign.html#elementos-del-diseno-de-un-proceso)
    *   [Formularios personalizados](15-QflowDesign.html#formularios-personalizados)
*   [Qflow Team](18-QflowTeam.html)
    *   [Introducción](18-QflowTeam.html#introduccion)
    *   [Organización de este manual](18-QflowTeam.html#organizacion-de-este-manual)
    *   [Modelo Organizacional](18-QflowTeam.html#modelo-organizacional)
    *   [Qflow Team](18-QflowTeam.html#id1)
*   [Qflow Admin](19-QflowAdmin.html)
    *   [Introducción](19-QflowAdmin.html#introduccion)
    *   [Descripción general de la interfaz de usuario](19-QflowAdmin.html#descripcion-general-de-la-interfaz-de-usuario)
    *   [Visor de licencias](19-QflowAdmin.html#visor-de-licencias)
    *   [Estadísticas](19-QflowAdmin.html#estadisticas)
    *   [Parámetros de sistema](19-QflowAdmin.html#parametros-de-sistema)
    *   [Propiedades extendidas](19-QflowAdmin.html#propiedades-extendidas)
    *   [Licencias](19-QflowAdmin.html#licencias)
    *   [Servicios de notificación](19-QflowAdmin.html#servicios-de-notificacion)
    *   [Administrar permisos](19-QflowAdmin.html#administrar-permisos)
    *   [Auditoría](19-QflowAdmin.html#auditoria)
    *   [Listado de parámetros de sistema](19-QflowAdmin.html#listado-de-parametros-de-sistema)
*   [Consumo de Q-points](21-Q-pointsConsumption.html)
    *   [Licenciamiento basado en usuarios](21-Q-pointsConsumption.html#licenciamiento-basado-en-usuarios)
    *   [Licenciamiento basado en consumo](21-Q-pointsConsumption.html#licenciamiento-basado-en-consumo)
*   [Conectores](34-ConnectorsIndex.html)
    *   [Configuración de Conectores desde una Tarea de Servicio](35-ConnectorParameterConfig.html)
    *   [Microsoft Teams](36.1-MicrosoftTeamsConnector.html)
    *   [Outlook](36.2-OutlookConnector.html)
    *   [Slack](36.3-SlackConnector.html)
    *   [Trello](36.4-TrelloConnector.html)
    *   [OpenAI](36.5-OpenAIConnector.html)
    *   [Jira Cloud](36.6-JiraCloudConnector.html)
    *   [Redmine](36.7-RedmineConnector.html)
    *   [DocuSign](36.8-DocuSignConnector.html)
    *   [Google Calendar](36.9-GoogleCalendarConnector.html)
    *   [Dropbox](36.11-DropboxConnector.html)
    *   [OneDrive](36.12-OneDriveConnector.html)
    *   [WhatsApp](36.13-WhatsAppTwilioConnector.html)
    *   [Microsoft Word](36.14-MicrosoftWordConnector.html)
    *   [ILovePDF](36.15-ILovePDFConnector.html)
*   [Desarrolladores](31-Development.html)
    *   [Interfaz de scripting](10-ScriptingInterface.html)
    *   [Web services API](20-WebServicesAPI.html)
    *   [Referencia de la biblioteca JavaScript](32-JavaScriptLibraryReference.html)
    *   [Tutoriales](31-Development.html#tutoriales)

[Siguiente](29-ReleaseNote.html "Novedades")

- - -

© Derechos de autor 2025, Urudata Software.


jQuery(function () { SphinxRtdTheme.Navigation.enable(true); }); window.dataLayer = window.dataLayer || \[\]; function gtag(){dataLayer.push(arguments);} gtag('js', new Date()); gtag('config', 'G-LMDS8S4B42', { 'anonymize\_ip': false, });
