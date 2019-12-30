pipeline {
  agent any
   // stages 包含一个或多个阶段(stage)的容器
  stages {
     // stage 阶段，pipleline流水线由一个或多个阶段(stage)组成，每个阶段必须有名称，这里build就是此阶段的名称
     stage('build') {
       // steps，阶段中的一个或多个具体步骤(step)的容器
       steps {
         # 这是是具体的步骤，真正”做事“的，不可再拆分的最小操作
         echo "hello world"
       }  
     }
  }
}
