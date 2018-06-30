+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = "2016-04-20T00:00:00"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "La asociación Espacual"
subtitle = "Asociarse a Espacual"

# Order that this section will appear in.
weight = 60

+++

Espacual nace en 2008 fruto de la colaboración de investigadores de diferentes áreas de conocimiento con el objeto de promover el uso de metodologías cualitativas, colaborar en la formación de jóvenes investigadores y difundir los resultados de las investigaciones cualitativas.

## Datos personales para el alta en la asociación

<form name="alta" method="POST" netlify>
  <p>
    <label>Nombre: <input type="text" name="nombre" /></label>   
  </p>
  <p>
    <label>Apellidos: <input type="text" name="apellidos" /></label>   
  </p>
  <p>
    <label> Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label> Dirección: <input type="text" name="direccion" /></label>   
  </p>  
  <p>
    <label> Población: <input type="text" name="poblacion" /></label>   
  </p>  
  <p>
    <label> Código postal: <input type="text" name="cp" /></label>   
  </p>
  <p>
    <label> Socio: <select name="role[]" multiple>
      <option value="Socio ordinario">ordinario</option>
      <option value="Socio estudiante">estudiante</option>
    </select></label>
  </p>
  <p>
    <label> Universidad: <input type="text" name="universidad" /></label>   
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

Para asociarte a espacual primero debes solicitar tu admisión rellenando el siguiente impreso en línea: [rellenar solicitud de admisión](https://docs.google.com/forms/d/e/1FAIpQLSe5udzvKiKeoLklSMnAgCfdEbeGs4kgbAwEemU3xpdBNDsEsQ/viewform)

Posteriormente puedes ir a la página donde se realiza el ingreso de las cuotas de los socios: [cuotas de los socios](https://espacual.netlify.com/talk/asociate-espacual/)




