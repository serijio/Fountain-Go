# **Fountain-Go**
*Date amor, bebe agua*

| [![Fountain&GO](https://github.com/serijio/Fountain-Go/blob/main/final_logo.png)](https://github.com/serijio/Fountain-Go) | Fountain&GO, aplicación creada y realizada en equipo junto a mi compañero @LordGrim551, nació con el objetivo de proporcionar a las personas de cualquier país la facilidad de localizar fuentes de agua potable allá donde estén; evitando así el gasto innecesario en botellas de plástico desechables. |
| --- | --- |

<br/>
<br/>

# **Diseño:**
<img src="https://github.com/serijio/Fountain-Go/blob/main/azul_base.png" width="112" height="50" alt="Azul base"><img src="https://github.com/serijio/Fountain-Go/blob/main/azul_fondo.png" width="112" height="50" alt="Azul fondo"><img src="https://github.com/serijio/Fountain-Go/blob/main/letra.png" width="112" height="50" alt="Azul letra"><img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo2.png" width="112" height="50" alt="Azul circulo 2"><img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo4.png" width="112" height="50" alt="Azul circulo 4"><img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo5.png" width="112" height="50" alt="Azul circulo 5"><img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo6.png" width="112" height="50" alt="Azul circulo 6"><img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo3.png" width="112" height="50" alt="Azul circulo 6"><img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo1.png" width="112" height="50" alt="Azul circulo 1">

- **Colorimetría**: los colores principales de **Fountain&GO** son diferentes tonalidades de azul: el amarillo `#FFCA41` y el negro `#000000`.
  + Fondo de diversas pantallas: &ensp; `#b8ecec` <img src="https://github.com/serijio/Fountain-Go/blob/main/azul_fondo.png" width="15" height="15" alt="Azul fondo">
  + Títulos y fondo del logotipo: &ensp; `#1c46b4` <img src="https://github.com/serijio/Fountain-Go/blob/main/azul_base.png" width="15" height="15" alt="Azul base">
  + Letras de botones: &ensp; `#12c0e7` <img src="https://github.com/serijio/Fountain-Go/blob/main/letra.png" width="15" height="15" alt="Azul letra">
  + Otros tonos del fondo: &ensp; `#708cbc` <img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo2.png" width="15" height="15" alt="Azul circulo 2"> &ensp;`#78b4dc` <img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo4.png" width="15" height="15" alt="Azul circulo 4"> &ensp;`#309ce4` <img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo5.png" width="15" height="15" alt="Azul circulo 5"> &ensp;`#b8ccec` <img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo6.png" width="15" height="15" alt="Azul circulo 6"> &ensp;`#507cb4` <img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo3.png" width="15" height="15" alt="Azul circulo 3"> &ensp;`#18c4e4` <img src="https://github.com/serijio/Fountain-Go/blob/main/azul_circulo1.png" width="15" height="15" alt="Azul circulo 1">
  <br/>
  <details>
  <summary>Leer más</summary>
  La elección del azul (con sus diversas variaciones) fue una decisión simple. El agua se asocia comúnmente con este color; y como la aplicación gira en torno a las fuentes, era la opción más evidente. No obstante, la utilización de un solo tono puede resultar en un diseño demasiado "vacío"; ocurriendo lo inverso en caso de usar demasiado colorido. Es por esto que el número de tonalidades y su colocación están pensadas para generar armonía y evitar la sobrecarga visual.
</details>
<br/>
  
- **Fuentes**: se han utilizado las fuentes “*Jua*” (para los títulos) y “*Kanit*” (para el resto de textos, similar a utilizar “*Calibri”* o “*Arial”* en un documento de texto). “*Jua”* otorga a las letras una forma redondeada, recordando al flujo del agua.

<br/>
<br/>

# **Pantallas y sus funciones**
Dentro de **Fountain&GO**, las principales pantallas son:

|Pantalla|Función|
| :-: | :-: |
|Login|Permite a los usuarios que ya disponen de una cuenta acceder a la aplicación|
|Registro|Permite a los nuevos usuarios crear una cuenta|
|Mapa (pantalla principal)|Una vez iniciada la sesión, aparece un mapa (similar al de Google), con marcadores en las fuentes disponibles en esa zona|
|Notificaciones|Aquí se almacenan los avisos de actualizaciones, respuestas a las propuestas de fuentes, novedades de la aplicación...|
|Propuesta de fuente|Permite a los usuarios enviar un formulario con una propuesta de fuente nueva. Ya que la acción de los administradores es amplia pero, aún así, limitada, es posible que alguna fuente no sea inicialmente registrada, por lo que estas sugerencias ayudan a completar el mapa|
|Favoritos|Permite a los usuarios visualizar las fuentes que han guardado|
|Perfil|Permite modificar la información del usuario, tanto la indicada en el momento de la creación de la cuenta, como aspectos adicionales (como la foto de perfil)|

<br/>

> [!NOTE]
> Estas pantallas son las de un usuario por defecto

<br/>
<br/>

# **Actividades Android y organización**
Para una mejor explicación, la organización se va a dividir en pantallas independientes y pantallas dependientes de la barra de navegación (con sus respectivas subpantallas).

### Pantallas independientes

- **SplashScreen**: primera pantalla de la aplicación, presenta una animación de carga con el logotipo y el nombre
- **StartScreen**: ofrece la opción de iniciar sesión de 3 formas distintas
- **LoginScreen**: pantalla de inicio de sesión propia de la aplicación
- **RegisterScreen**: pantalla de registro propia de la aplicación
- **PreferencesScreen**: después de que un nuevo usuario introduzca los datos requeridos, se le solicitará información acerca de sus intereses
- **MiddleSplashScreen**: pantalla de carga intermedia entre la de preferencias y la principal

<br/>

### Pantallas dependientes de la barra de navegación:

- **MainActivityScreen**: pantalla principal de la aplicación; tanto a los nuevos usuarios como a los ya existentes se les redirige aquí después de introducir sus credenciales
    - **MainActivityScreen - See all selected** [^1]
        - MainActivityScreen - See all selected - Categories
- **SavedScreen**: pantalla que muestra los productos que el usuario ha marcado (no implica que se vayan a adquirir en el momento del marcado)
- **AddProductScreen**: pantalla que permite agregar un nuevo *TruequeProducto* al perfil del usuario
    - **CategoryScreen**: sub pantalla para seleccionar la categoría del producto
    - **BrandScreen**: sub pantalla para seleccionar la marca del producto
- **MessagesScreen**: pantalla que almacena las conversaciones entre usuarios, además de otras notificaciones (como interacciones de usuarios con los productos, actualizaciones de la aplicación...)
    - **ChatScreen**: sub pantalla individual de cada chat
- **UserScreen**: pantalla personal de cada usuario, donde se muestra su información y se ofrece la posibilidad de cambiar datos
    - **SettingsScreen**: sub pantalla para modificar los ajustes
    - **TruequePointsProScreen**: sub pantalla para suscribirse al servicio premium de *TruequeWorld*
    - **UserDetailsScreen**: sub pantalla para modificar los datos del usuario
    - **PrivacityScreen**: sub pantalla para ver los tratados de privacidad y protección de datos de la aplicación
    - **MyWalletScreen**: sub pantalla para añadir o eliminar tarjetas de crédito; indica también el saldo actual introducido en la aplicación

  <br/>
  <br/>

[^1]: Para conocer más detalles acerca de las pantallas, acceder al pdf del [Figma](https://github.com/TheRockex/TruequeWorld/blob/main/TruequeWorld.pdf)
