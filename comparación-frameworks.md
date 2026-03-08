FRAMEWORK BASADO EN COMPONENTES:
Un framework basado en componentes (como Bootstrap) proporciona elementos ya diseñados y listos para usar, como botones, tarjetas, menús de navegación o formularios.

Características clave:
-Trae estilos y scripts predefinidos.
-Solo tienes que aplicar las clases correspondientes para obtener un diseño funcional.
-Ideal para prototipos rápidos o sitios que no necesitan mucho diseño personalizado.

Ejemplo:
<button class="btn btn-primary">Enviar</button>
*btn y btn-primary ya tienen estilo definido por el framework.
*No necesitas escribir CSS para que se vea bien.

Cuándo usarlo:
-Prototipos rápidos
-Sitios donde no necesitas mucho diseño personalizado
-Equipos que necesitan consistencia rápida en estilos

FRAMEWORK BASADO EN UTILIDADES:
Un framework basado en utilidades (como Tailwind CSS) no da componentes completos, sino clases pequeñas que aplican estilos específicos.

Características clave:
-Cada clase hace una sola cosa: color, tamaño, margen, padding, tipografía…
-Mayor control sobre el diseño final.
-Requiere conocimientos básicos de CSS para combinar las utilidades correctamente.

Ejemplo:
<button class="bg-blue-500 text-white px-4 py-2 rounded">
Enviar
</button>
*Cada clase (bg-blue-500, text-white, px-4, rounded) controla una propiedad del botón.
*Puedes personalizar totalmente su aspecto sin escribir CSS adicional.
Cuándo usarlo:
*Proyectos que necesitan diseño muy personalizado
*Cuando quieres un control total sobre cada detalle
*Para desarrolladores que ya entienden CSS
ventajas y desventajas
*Framework basado en componentes (Bootstrap):
-Facilidad de uso: Muy fácil, listo para usar.
-Velocidad: Rápido para prototipos.
-Personalización: Limitada, hay que sobrescribir estilos.
-Consistencia: Consistente por defecto.
-Tamaño de código: Puede ser grande si no se optimiza.

\*Framework basado en utilidades (Tailwind CSS):
-Facilidad de uso: Requiere práctica combinando utilidades.
-Velocidad: Más lento al inicio, rápido a largo plazo.
-Personalización: Muy alta, cada detalle se puede ajustar.
-Consistencia: Depende de ti crear la consistencia.
-Tamaño de código: Más ligero si se purga lo no usado.

EJEMPLOS DE USO O SITUACIONES:

\*Framework basado en componentes (Bootstrap):
-Landing page rápida
-Formularios y botones listos
-Dashboards rápidos

\*Framework basado en utilidades (Tailwind):
-Portfolio personal con diseño único
-Sitios que requieren responsive y adaptaciones detalladas
-Componentes con estilos diferentes en cada parte del sitio
