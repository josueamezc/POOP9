@startuml
package "POOP9" #DDDDDD{
    class SerVivo{
        -nombre:String
        -edad:int
        -peso:float
        +dormir()
        +comer()
    }

    class mascota{
        -color:String
        -raza:String
        -tamaño:char
        +jugar()
        +correr()
    }
    abstract class claseAbstracta{
        +metodoAbstracto:String
    }
    interface interfaz{
        +metodoDeInterfacez:double

    }
}


SerVivo <|-- mascota
@enduml