  pipeline {
 agent { label { label 'built-in'
                 customWokspace '/data/pipe'
 }
}

stages { 
      stage ('master') {  
steps { sh"mkdir uday"
sh " service httpd restart"}


}
stage ('QA') { agent { label 'QA'}

steps { sh " mkdir uda" }




}

}

}










