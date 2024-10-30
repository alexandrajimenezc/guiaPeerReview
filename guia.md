## Guía Paso a Paso para Realizar un Peer Review en Angular 🚀

El peer review es una práctica fundamental en el desarrollo de software que permite mejorar la calidad del código, detectar errores tempranamente y promover el aprendizaje entre el equipo. En este contexto, creamos una guía detallada para realizar un peer review efectivo de forma 'ideal', si las condiciones lo permiten en proyectos Angular.

**¿Qué es un Peer Review?**

Es un proceso en el que un desarrollador revisa el código de otro miembro del equipo con el objetivo de identificar posibles mejoras, errores o incumplimientos de las normas de codificación.

**Pasos para Realizar un Peer Review en Angular**

- **Establecer Normas y Guías:** Guía de estilo, convenciones de commit, criterios de revisión.
- **Preparación del Código para la Revisión:** Commits atómicos, descripción clara, pruebas unitarias.
- **Selección del Revisor:** Experiencia, objetividad.
- **Proceso de Revisión:** Lectura detallada, comparación con las normas, búsqueda de errores, evaluación de la legibilidad, sugerencias de mejora.
- **Comunicación:** Feedback constructivo, diálogo abierto, herramientas de colaboración.
- **Resolución de Comentarios:** Implementación de los cambios, cierre de la revisión.

### Pasos para Realizar un Peer Review en Angular

1. **Establecer Normas y Guías:**

   - **Guía de estilo:** Definir un conjunto claro de reglas sobre cómo escribir el código en Angular, incluyendo indentación, nombres de variables, formato, etc.
   - **Convenciones de commit:** Establecer cómo deben realizarse los commits para facilitar el seguimiento de los cambios.
   - **Criterios de revisión:** Determinar qué aspectos se evaluarán durante la revisión, como la corrección del código, la eficiencia, la legibilidad, la adherencia a las buenas prácticas de Angular y la cobertura de pruebas.

2. **Preparación del Código para la Revisión:**

   - **Commits atómicos:** Asegurarse de que cada commit se enfoque en una única característica o corrección.
   - **Descripción clara:** Incluir una descripción concisa y detallada de los cambios realizados en cada commit.
   - **Pruebas unitarias:** Verificar que las pruebas unitarias estén actualizadas y cubran adecuadamente el código modificado.

3. **Selección del Revisor:**

   - **Experiencia:** Elegir a un revisor con experiencia en el área del código que se está revisando.
   - **Objetividad:** Buscar un revisor que no esté directamente involucrado en el desarrollo de la funcionalidad.

4. **Proceso de Revisión:**

   - **Lectura detallada:** Leer el código línea por línea, prestando atención a la lógica, la estructura y la sintaxis.
   - **Comparación con las normas:** Verificar que el código cumpla con las normas y guías establecidas.
   - **Búsqueda de errores:** Identificar posibles errores de lógica, sintaxis o tipografía.
   - **Evaluación de la legibilidad:** Asegurarse de que el código sea fácil de entender y mantener.
   - **Sugerencias de mejora:** Proponer cambios para mejorar la eficiencia, la reutilización del código o la claridad.

5. **Comunicación:**

   - **Feedback constructivo:** Proporcionar comentarios claros y específicos, evitando críticas personales.
   - **Diálogo abierto:** Establecer un diálogo abierto entre el autor y el revisor para discutir los cambios propuestos.
   - **Herramientas de colaboración:** Utilizar herramientas como GitHub, GitLab o Bitbucket para facilitar la revisión y el seguimiento de los cambios.

6. **Resolución de Comentarios:**
   - **Implementación de los cambios:** El autor del código debe implementar los cambios sugeridos por el revisor.
   - **Cierre de la revisión:** Una vez que se han realizado los cambios, el revisor debe verificar que se hayan abordado todos los comentarios.

**Herramientas Útiles para Peer Review en Angular**

- GitHub
- GitLab
- Bitbucket
- SonarQube
- ESLint

* **GitHub:** Permite realizar revisiones de código mediante pull requests, comentarios y etiquetas.
* **GitLab:** Ofrece funcionalidades similares a GitHub, incluyendo la posibilidad de crear pipelines de CI/CD.
* **Bitbucket:** Proporciona herramientas para la gestión de código, incluyendo la revisión por pares.
* **SonarQube:** Analiza el código estático y proporciona métricas sobre la calidad del código, como la complejidad ciclomática y la cobertura de código.
* **ESLint:** Un linter de código que ayuda a identificar errores comunes y a garantizar la consistencia del estilo de codificación.

**Beneficios del Peer Review**

- Mejora de la calidad del código
- Promoción del aprendizaje
- Establecimiento de estándares
- Fomento de la colaboración

* **Mejora de la calidad del código:** Al detectar y corregir errores tempranamente, se reduce el riesgo de introducir bugs en producción.
* **Promoción del aprendizaje:** Los desarrolladores aprenden de los demás y comparten conocimientos.
* **Establecimiento de estándares:** Ayuda a mantener un nivel de calidad consistente en todo el proyecto.
* **Fomento de la colaboración:** Fomenta el trabajo en equipo y la comunicación entre los miembros del equipo.

**Consejos Adicionales:**

- Regularidad
- Rotación de revisores
- Automatización
- Cultura de mejora continua

* **Regularidad:** Realizar revisiones de código de forma regular para garantizar una alta calidad.
* **Rotación de revisores:** Variar los revisores para obtener diferentes perspectivas.
* **Automatización:** Utilizar herramientas de automatización para agilizar el proceso de revisión.
* **Cultura de mejora continua:** Fomentar una cultura en la que se valore el feedback y se busque la mejora constante.

**Al implementar un proceso de peer review efectivo en tu equipo de desarrollo Angular, podrás crear aplicaciones de mayor calidad y garantizar la satisfacción de tus usuarios.**

### Nomenclatura y Estilo

- **Nombres de variables:**
  - **Significativos:** Los nombres de las variables deben reflejar claramente su propósito.
  - **CamelCase:** Utiliza CamelCase para variables y propiedades (ejemplo: `firstName`, `customerList`).
  - **Tipo de dato:** Si es relevante, incluye el tipo de dato en el nombre (ejemplo: `isComplete`, `userData`).
- **Nombres de funciones:**
  - **Verbos:** Los nombres de las funciones deben comenzar con un verbo que indique la acción que realizan (ejemplo: `getUserData`, `calculateTotal`).
  - **Concisos:** Evita nombres demasiado largos, pero asegúrate de que sean claros.
- **Comentarios:**
  - **Explicativos:** Los comentarios deben explicar el "por qué" del código, no el "qué".
  - **Concisos:** Los comentarios deben ser concisos y fáciles de entender.
  - **Actualizados:** Mantén los comentarios actualizados cuando modifiques el código.
- **Longitud de las líneas:**
  - **Máximo 80 caracteres:** Se recomienda mantener las líneas de código por debajo de 80 caracteres para mejorar la legibilidad.
- **Espaciado:**
  - **Espacios en blanco:** Utiliza espacios en blanco para mejorar la legibilidad del código.
  - **Indentación:** Utiliza una indentación consistente (generalmente 4 espacios) para resaltar la estructura del código.
- **Convenciones de estilo:**
  - **Angular Style Guide:** Sigue las convenciones de estilo oficiales de Angular para mantener una coherencia en todo el proyecto.

### Prácticas Adicionales para una Mejor Calidad de Código

- **Principio de Responsabilidad Única (SRP):** Cada componente, servicio o directiva debe tener una única responsabilidad.
- **Inyección de dependencias:** Utiliza la inyección de dependencias para mejorar la testabilidad y la modularidad.
- **Pipes puros vs impuros:** Comprende la diferencia entre pipes puros e impuros y utilízalos de manera adecuada.
- **Manejo de errores:** Implementa un manejo de errores robusto para evitar que la aplicación se bloquee.
- **Pruebas unitarias:** Escribe pruebas unitarias para garantizar la calidad del código y detectar errores temprano.
- **Linters:** Utiliza linters como TSLint o ESLint para mantener un estilo de código consistente y detectar posibles errores.
- **Formateadores:** Herramientas como Prettier pueden ayudarte a formatear automáticamente el código y ahorrar tiempo.
- **Documentación:** Documenta tu código utilizando herramientas como JSDoc para facilitar la comprensión y el mantenimiento a largo plazo.

### Ejemplo de Código con Buenas Prácticas

```typescript
// services/user.service.ts
import { Injectable } from "@angular/core";

@Injectable({
  providedIn: "root",
})
export class UserService {
  constructor() {}

  /**
   * Retrieves a user by its ID
   * @param userId The ID of the user to retrieve
   */
  getUserById(userId: number): Observable<User> {
    // ... implementation
  }
}
```

### Incorporando estas Prácticas en tu Proyecto

- **Establecer un estilo de guía:** Define un estilo de guía para tu equipo y asegúrate de que todos lo sigan.
- **Utilizar herramientas:** Emplea herramientas como linters y formateadores para automatizar la aplicación de las buenas prácticas.
- **Revisar el código:** Realiza revisiones de código regularmente para garantizar la calidad y detectar posibles problemas.
- **Formar a tu equipo:** Asegúrate de que todos los miembros del equipo estén familiarizados con las buenas prácticas y las razones detrás de ellas.

**Beneficios de seguir estas prácticas:**

- **Mayor legibilidad:** El código será más fácil de entender y mantener.
- **Menor cantidad de errores:** Las buenas prácticas ayudan a prevenir errores comunes.
- **Mayor colaboración:** Un estilo de código consistente facilita la colaboración entre desarrolladores.
- **Mejor rendimiento:** Un código bien estructurado puede mejorar el rendimiento de la aplicación.

Al seguir estas pautas, podremos crear aplicaciones Angular de alta calidad, más fáciles de mantener y escalar.

## EJEMPLO DOCUMENTO EN CASO DE NECESITAR

## Revisión de código: Componente de usuario

**Fecha:** 2023-11-15

**Revisor:** Juan Pérez
**Autor:** María López

**Ámbito:** Componente de usuario

**Cambios:**

- Se ha añadido un nuevo campo para mostrar la dirección del usuario.
- Se ha mejorado la validación del formulario para evitar errores comunes.
- Se ha optimizado el rendimiento al utilizar un observable en lugar de múltiples suscripciones.

**Razones:**

- El nuevo campo de dirección es necesario para la nueva funcionalidad de geolocalización.
- La validación del formulario se ha mejorado para garantizar que los datos ingresados sean correctos.
- El uso de un observable ha simplificado el código y mejorado el rendimiento.

**Comentarios:**

- Se sugiere utilizar una biblioteca de validación de formularios para simplificar el proceso.
- Se podría considerar agregar una prueba unitaria para el nuevo campo de dirección.

**Próximos pasos:**

- Implementar la funcionalidad de geolocalización.
- Agregar una prueba unitaria para el nuevo campo de dirección.



## Contribuyendo 🖇️
Escribe un msj a @soygeekgirl


## Expresiones de Gratitud 🎁
## Mi extensión en angular
Contiene referencia de varias guias de estilo de angular

# ts-angular-snippets-soygeekgirl
https://marketplace.visualstudio.com/items?itemName=ts-angular-snippets-soygeekgirl.ts-angular-snippets-soygeekgirl