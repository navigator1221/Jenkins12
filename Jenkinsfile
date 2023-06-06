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
                    def contenido = "Gustavo Adrián Cerati (Barracas, Buenos Aires, 11 de agosto de 1959-Núñez, Buenos Aires, 4 de septiembre de 2014), conocido como Gustavo Cerati, fue un músico, cantautor y productor discográfico argentino que obtuvo reconocimiento internacional por haber sido el líder, vocalista, compositor y guitarrista de la banda de rock Soda Stereo. Parte de la prensa especializada y músicos lo consideran como uno de los artistas más influyentes del rock latinoamericano."
                    writeFile(file: "salida_ejercicio3.txt", text: contenido)
                }
            }
        }
    }
}
