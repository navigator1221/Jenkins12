pipeline
{
  agent any
  stages
  {
    stage ("Hola mundo")
    {
      steps
      {
        echo "Hola Mundo"
      }
    }
    stage ("Mover archivo")
    {
      steps
      {
        bat 'move "C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\PPL_8\\Jenkinsfile" "C:\\"'
      }
    }
 }
}
