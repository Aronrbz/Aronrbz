## Hi, I'm Aron 👋👨‍💻

<h1>Nice</h1>
<h5>Nice</h5>

 if you want to contact me 🔍:

- [LinkedIn](https://cl.linkedin.com/in/aaronrbz) 
- <a href="mailto:ar.bustos@duocuc.cl">Email</a> 📧

<details>
  <summary>Click here to see my skills</summary>
  <p>
   
       // Primero crearemos una Clase base para los lenguajes (puedes pegarlos en tu ide y funcionara)

       /* Clase Lenguaje.java */
        public class Lenguaje {
            private String nombre;
            private String tipo;
        
            public Lenguaje(String nombre, String tipo) {
                this.nombre = nombre;
                this.tipo = tipo;
            }
        
            public String getNombre() {
                return nombre;
            }
        
            public void setNombre(String nombre) {
                this.nombre = nombre;
            }
        
            public String getTipo() {
                return tipo;
            }
        
            public void setTipo(String tipo) {
                this.tipo = tipo;
            }
        
            public void mostrarInformacion() {
                System.out.println("Lenguaje: " + nombre + " | Tipo: " + tipo);
            }
          }

      //////////////////////////////////////////////////////////////////////////
                           Usaremos Herencias y Polimorfismo
      //////////////////////////////////////////////////////////////////////////


      // Clases para lenguajes Frontend
      public class LenguajeFrontend extends Lenguaje {
      
        public LenguajeFrontend(String nombre) {
            super(nombre, "Frontend");
        }
    
        @Override
        public void mostrarInformacion() {
            super.mostrarInformacion();
            System.out.println("Este es un lenguaje de Frontend, perfecto para interfaces dinámicas y modernas.");
        }
      }
      

      // Clases para lenguajes Backend
      public class LenguajeBackend extends Lenguaje {
    
        public LenguajeBackend(String nombre) {
            super(nombre, "Backend");
        }
    
        @Override
        public void mostrarInformacion() {
            super.mostrarInformacion();
            System.out.println("Este es un lenguaje de Backend, ideal para lógica robusta y escalabilidad.");
        }
      }


      
      // Clases para lenguajes de Base de Datos
      public class LenguajeBaseDeDatos extends Lenguaje {
      
        public LenguajeBaseDeDatos(String nombre) {
            super(nombre, "Base de Datos");
        }
    
        @Override
        public void mostrarInformacion() {
            super.mostrarInformacion();
            System.out.println("Este es un lenguaje especializado en la gestión de datos persistentes.");
        }
      }


      
      // Lenguajes y tecnologías específicos
      
      // Frontend
      public class HTML extends LenguajeFrontend {
          public HTML() {
              super("HTML");
          }
      }
      
      public class CSS extends LenguajeFrontend {
          public CSS() {
              super("CSS");
          }
      }

      
      public class JavaScript extends LenguajeFrontend {
          public JavaScript() {
              super("JavaScript (jQuery)");
          }
      }


      
      // Frameworks Frontend
      public class Angular extends JavaScript {
          public Angular() {
              super();
              setNombre("Angular");
          }
      
        @Override
        public void mostrarInformacion() {
            System.out.println("Framework: " + getNombre() + " | Basado en: JavaScript");
        }
      }


      
      // Backend
      public class Java extends LenguajeBackend {
          public Java() {
              super("Java");
          }
      }


      
      // Frameworks Backend
      public class Spring extends Java {
          public Spring() {
              super();
              setNombre("Spring");
          }
    
        @Override
        public void mostrarInformacion() {
            System.out.println("Framework: " + getNombre() + " | Basado en: Java");
        }
      }
      
      public class JavaEnterpriseEdition extends Java {
          public JavaEnterpriseEdition() {
              super();
              setNombre("Java Enterprise Edition");
          }
      
        @Override
        public void mostrarInformacion() {
            System.out.println("Framework: " + getNombre() + " | Basado en: Java");
        }
      }
      
      public class Python extends LenguajeBackend {
          public Python() {
              super("Python");
          }
      }
      
      public class Django extends Python {
          public Django() {
              super();
              setNombre("Django");
          }
    
        @Override
        public void mostrarInformacion() {
            System.out.println("Framework: " + getNombre() + " | Basado en: Python");
        }
      }

      
      // Base de Datos
      public class PostgreSQL extends LenguajeBaseDeDatos {
          public PostgreSQL() {
              super("PostgreSQL");
          }
      }
      
      public class SQLite extends LenguajeBaseDeDatos {
          public SQLite() {
              super("SQLite");
          }
      }
      
      public class Oracle extends LenguajeBaseDeDatos {
          public Oracle() {
              super("Oracle");
          }
      }
      
      public class MySQL extends LenguajeBaseDeDatos {
          public MySQL() {
              super("MySQL");
          }
      }


      
      //////////////////////////////////////////////////////////////////////////
                           Lenguajes que estoy aprendiendo
      //////////////////////////////////////////////////////////////////////////
      
      public class CSharp extends LenguajeBackend {
          public CSharp() {
              super("C#");
          }
      }
      
      public class DotNet extends CSharp {
          public DotNet() {
              super();
              setNombre(".Net");
          }
    
        @Override
        public void mostrarInformacion() {
            System.out.println("Framework: " + getNombre() + " | Basado en: C#");
        }
      }


      
      // Main class para probar todo (opcional, si decides usarlo en un IDE)
      
      public class Main {
          public static void main(String[] args) {
              Lenguaje html = new HTML();
              Lenguaje css = new CSS();
              Lenguaje js = new JavaScript();
              Lenguaje angular = new Angular();
              Lenguaje java = new Java();
              Lenguaje spring = new Spring();
              Lenguaje jee = new JavaEnterpriseEdition();
              Lenguaje python = new Python();
              Lenguaje django = new Django();
              Lenguaje postgres = new PostgreSQL();
              Lenguaje sqlite = new SQLite();
              Lenguaje oracle = new Oracle();
              Lenguaje mysql = new MySQL();
              Lenguaje csharp = new CSharp();
              Lenguaje dotnet = new DotNet();
    
            Lenguaje[] lenguajes = {html, css, js, angular, java, spring, jee, python, django, postgres, sqlite, oracle, mysql, csharp, dotnet};
    
            for (Lenguaje lenguaje : lenguajes) {
                lenguaje.mostrarInformacion();
                System.out.println("------------------------------------");
            }
        }
      }
      
   </p>
</details>

<!--
**Aronrbz/Aronrbz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
