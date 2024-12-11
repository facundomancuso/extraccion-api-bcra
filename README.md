INTRODUCCIÓN: Este código permite consultar dos endpoints de la API del Banco Central de la República Argentina. Los datos se obtienen en formato json y son pasados a dataframes para su manipulación. Se realizan almacenamiento en datalakes por diferentes capas (bronze, silver, gold) y se implementan las limpiezas y transformaciones necesarias.

IMPORTANTE: Recuerda crear un archivo denominado 'pipeline.conf' que dentro debe tener tu key/token para las consultas GET.

EJEMPLO:

Tu archivo 'pipeline.conf' debe verse así:

  [bcra_api]
  access_token = TU_TOKEN_API
  
Puedes obtener tu key/token en: https://estadisticasbcra.com/api/registracion
