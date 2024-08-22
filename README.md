![image](https://github.com/user-attachments/assets/ca2ea0e1-9da7-48b8-b9e1-9fd01524027c)


## Hi, I'm Aron 👋👨‍💻

A little about me:

My name is Aron Bustos and I'm from Santiago Chile. Am currently working as a project engineer for a consulting firm called “R y C consultores”, where I perform software engineering services for one of our clients “Principal Financial Group” and their business “AFP Cuprum” as outsourcing of the consulting firm. 

Previously, I worked in other consulting firms with clients such as Banco de Chile, being here specialist in disaster recovery plan (known as DRP). Am also a full stack developer using technologies such as django, mySQL, js, git, etc.

I'm a programmer analyst graduated from DuocUC and I intend to continue my studies, from 2025 as a computer engineer, at the Diego Portales University. 



if you want to contact me 🔍:

- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://cl.linkedin.com/in/aaronrbz)
- [![Email](https://img.shields.io/badge/Email-%230078D4.svg?style=for-the-badge&logo=mail.ru&logoColor=white)](mailto:ar.bustos@duocuc.cl)
- <a href="https://discord.com/users/2862" target="_blank"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/discord.svg" alt="Discord" width="30" height="30"></a>

<h4>MY GitHub Stats</h4>

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Aronrbz&layout=compact&theme=radical)

<h4>Lenguajes y Frameworks</h4>

<div style="display: flex; gap: 15px;">

  <a href="https://www.java.com" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/java-coffee-cup-logo--v1.png" width="48" height="48" style="border-radius: 10%;"/>
  </a>

  <a href="https://www.python.org" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/python--v1.png" width="48" height="48" style="border-radius: 10%;"/>
  </a>

  <a href="https://html.com" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/html-5--v1.png" width="48" height="48" style="border-radius: 10%;"/>
  </a>

  <a href="https://www.w3schools.com/css/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/css3.png" width="48" height="48" style="border-radius: 10%;"/>
  </a>

  <a href="https://www.javascript.com" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/javascript--v1.png" width="48" height="48" style="border-radius: 10%;"/>
  </a>

  <a href="https://angular.io" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/angularjs.png" width="48" height="48" style="border-radius: 10%;"/>
  </a>
  
  <a href="https://git-scm.com/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/git.png" width="48" height="48" style="border-radius: 10%;"/>
 </a>

 <a href="https://github.com/" target="_blank">
    <img src="https://img.icons8.com/ios-glyphs/48/000000/github.png" width="48" height="48" style="border-radius: 10%;"/>
</a>

<a href="https://en.wikipedia.org/wiki/Database" target="_blank">
    <img src="https://img.icons8.com/ios-filled/50/000000/database.png" width="48" height="48" style="border-radius: 10%;"/>
</a>


</div>



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
