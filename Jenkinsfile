pipeline
{
    agent any
    stages
    {
        stage("Creacion del fichero")
        {
            steps
            {
                script
                {
                    def contenido = "Bienvenido al pipeline del ejercicio3"
                    writeFile(file: "salida_ejercicio3.txt", text: contenido)
                }
            }
        }
    }
}
