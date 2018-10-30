node('master'){
    stage('stage2'){
        echo"Just Demo!!!"
        
     stage('deploy')
        {
               Environment('Test01')
                {
                       echo"Deploy in Test01 environment"
                       Replace tocken:
                       (
                           EnvSuffix='test01'
                           jar name=jarWX-'EnvSuffix'.jar
                           CopyJars='AllIndependentJars.xml'
                       )
                           
                }
        }
    }
}
