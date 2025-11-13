Bienvenido a la documentación de Qflow — Qflow Cloud
* [Qflow](https://qflowbpm.com/es/)
* [Foro](https://forum.qflowbpm.com/)
* [Centro de Ayuda](https://qflowbpm.com/es/centro-de-ayuda/)
* [Contáctanos](https://qflowbpm.com/es/contacto/)

[Qflow](#)
Cloud (latest) 5.5
OnPremise (latest) 5.2
OnPremise 5.1.1
OnPremise English Español

selectElement('versionSelect', getVersion());
selectElement('languageSelect', getLanguage());

function selectElement(id, valueToSelect) {
  let element = document.getElementById(id);
  element.value = valueToSelect;
}

function getLanguage() {
  if (window.location.href.includes('/es/')) {
    return '/es/';
  } else {
    return '/en/';
  }
}

function getVersion() {
  if (window.location.href.includes('/qflowcloud/')) {
    return '/qflowcloud/';
  } else if (window.location.href.includes('/qflow5_1_1/')) {
    return '/qflow5_1_1/';
  } else if (window.location.href.includes('/qflow5_2/')) {
    return '/qflow5_2/';
  } else {
    return '/qflow5_5/';
  }
}

function redirectToSite(url) {
  var http = new XMLHttpRequest();
  http.onreadystatechange = function() {
    if (http.readyState === 4) {
      if (http.status !== 404) {
        window.location.href = url;
      } else {
        window.location.href = url.replace(url.substr(url.lastIndexOf('/') + 1), 'index.md');
      }
    }
  }
  http.open('HEAD', url, true);
  http.send();
}

Inicio
* [Novedades](29-ReleaseNote.md)
* [Introducción a Qflow](01-QflowIntroduction.md)
* [Tutoriales](TutorialsIndex.md)
* [Qflow Task](04-QflowTask.md)
* [Qflow Design](15-QflowDesign.md)
* [Qflow Team](18-QflowTeam.md)
* [Qflow Admin](19-QflowAdmin.md)
* [Consumo de Q-points](21-Q-pointsConsumption.md)
* [Conectores](34-ConnectorsIndex.md)
* [Desarrolladores](31-Development.md)

[Siguiente](29-ReleaseNote.md "Novedades")

© Derechos de autor 2025, Urudata Software.
