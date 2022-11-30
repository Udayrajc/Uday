pipeline { 
agent {
label { 
        label 'QA'
       customWorkspace '/data/pipe' }
}
stages {
stage ('master') { sh " vi index.html"
                  sh " cp -r index.html /var/www/html" }


}

}


}


