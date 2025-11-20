classDiagram
    class Maps {
        -String tipo
        -tipObjetes objetinipo
        -String elemento
        -List~Recursor~ recurso
        -List~Vilanos~ vilanos
        -String css
        +general(Mapad)
        +codecarRecursos()
        +codecarVilanos()
    }

    class Recursos {
        -int posx
        -int popy
        -String formalDelRecurso
        -bool activo
        +dbLightRecursol()
        +estalactivo()
        +desaparecer()
    }

    class Personaje {
        -int x
        -int y
        -String aprile
        -String nombre
        +mover(direccion)
        +dbLight()
        +bonzini()
        +int gpKXU
        +int gptYU
        +getSprint()
    }

    class Vilano {
        +robot()
        +mover(Maxiorlo())
    }

    class Jaguider {
        -int candida@Diamante
        -int candida@Forest
        -int candida@FuenteDeLuz
        +recoger()
        +mostrarinv()
        +objetino()
    }

    class Alsa6 {
        +a.yudis()
    }

    class GameManager {
        -int tiempoRestante
        -int vista
        -int objetinologua = 50
        -int objetinobedera = 50
        -int objetineRoca = 5
        +iniciativa(megro)
        +actualizar(Tiempo())
        +verificar(victoria)
        +verificar(borrosa)
    }

    Maps "1" *-- "many" Recursos : contains
    Maps "1" *-- "many" Vilano : contains
    Personaje <|-- Jaguider : inheritance
    Jaguider --> Recursos : recoger
    GameManager --> Maps : manages
    GameManager --> Personaje : controls
    Vilano --|> Personaje : inheritance
    Alsa6 --> Jaguider : assists
