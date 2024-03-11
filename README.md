![This is me](https://github.com/PabloRuizdeOtero/PabloRuizdeOtero/blob/main/logoGit.png)
```kotlin
class Persona(val nombre: String, val profesion: String, val descripcion: String)

  fun sobreMi(): Persona {
      val pabloRuiz = Persona(
          nombre = "Pablo Ruiz",
          profesion = "Desarrollador de Software",
          descripcion = "Apasionado por la tecnología y el desarrollo de software,
          con especial interés en el desarrollo de aplicaciones móviles
          y la inteligencia artificial."
      )
      return pabloRuiz
  }

  fun main() {
      val sobreMi = sobreMi()
      println("Nombre: ${sobreMi.nombre}")
      println("Profesión: ${sobreMi.profesion}")
      println("Descripción: ${sobreMi.descripcion}")
  }
```
```javascript
const PabloRuiz = {
  code: [
    "DESARROLLO MOBILE", "DESARROLLO WEB",
    "JAVA", "C#", "PYTHON", "CSS3", "HTML5",
    "KOTLIN", ".NET", "JAVASCRIPT", "MySqL", "PHP", "FIREBASE"
  ],
  entornos: [
    "Android Studio",
    "Django",
    "Unity",
    "Visual Studio"
  ],
  proyectos: [],

  agregarHabilidad(habilidad) {
    if (!this.code.includes(habilidad)) {
      this.code.push(habilidad);
    }
  },

  agregarEntorno(entorno) {
    if (!this.entornos.includes(entorno)) {
      this.entornos.push(entorno);
    }
  },

  agregarProyecto(proyecto) {
    this.proyectos.push(proyecto);
  },

  mostrarHabilidades() {
    console.log('Habilidades:', this.code.join(', '));
  },

  mostrarEntornos() {
    console.log('Entornos de Desarrollo:', this.entornos.join(', '));
  },

  mostrarProyectos() {
    if (this.proyectos.length > 0) {
      this.proyectos.forEach((proyecto, index) => {
        console.log(`Proyecto ${index + 1}: ${proyecto.nombre} - ${proyecto.descripcion}`);
      });
    } else {
      console.log('No hay proyectos agregados aún.');
    }
  }
};

// Uso de las funciones
PabloRuiz.agregarHabilidad('JavaFx');
PabloRuiz.agregarEntorno('Intellij');
PabloRuiz.agregarProyecto({ nombre: 'App de Finanzas Personales',
                            descripcion: 'Una aplicación móvil para gestionar finanzas personales.' });

PabloRuiz.mostrarHabilidades();
PabloRuiz.mostrarEntornos();
PabloRuiz.mostrarProyectos();

```
```c#
using System;
using System.Collections.Generic;

public class RedSocial
{
    public string Nombre { get; set; }
    public string Usuario { get; set; }

    public RedSocial(string nombre, string usuario)
    {
        Nombre = nombre;
        Usuario = usuario;
    }
}

class Program
{
    public static List<RedSocial> MisRedesSociales()
    {
        return new List<RedSocial>
        {
            new RedSocial("LinkedIn", "www.linkedin.com/in/pablo-ruiz-de-otero-80986422b"),
            new RedSocial("GitHub", "PabloRuizdeOtero")
        };
    }

    static void Main(string[] args)
    {
        var misRedes = MisRedesSociales();
        foreach (var red in misRedes)
        {
            Console.WriteLine($"Red Social: {red.Nombre}, Usuario: {red.Usuario}");
        }
    }
}

```
