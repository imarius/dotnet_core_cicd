pipeline {
    agent any
    stages {
        stage('Build Docker Container'){
           steps{
               sh 'docker build'
            }
         }
      //   stage('Restore packages'){
      //      steps{
      //          sh 'dotnet restore NetCoreCICI.sln'
      //       }
      //    }
      //   stage('Clean'){
      //      steps{
      //          sh 'dotnet clean NetCoreCICI.sln --configuration Release'
      //       }
      //    }
      //   stage('Build'){
      //      steps{
      //          sh 'dotnet build NetCoreCICI.sln --configuration Release --no-restore'
      //       }
      //    }
      //   stage('Test: Unit Test'){
      //      steps {
      //           sh 'dotnet test CoreWeatherAPI.Tests/CoreWeatherAPI.Tests.csproj --configuration Release --no-restore'
      //        }
      //     }
      //   stage('Publish'){
      //        steps{
      //          sh 'dotnet publish CoreWeatherAPI/CoreWeatherAPI.csproj --configuration Release --no-restore'
      //        }
      //   }
    }
}