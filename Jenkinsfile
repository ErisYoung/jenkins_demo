pipeline {
  agent any

  parameters {
    booleanParam(defaultValue: true, description: '', name: 'p_userFlag')
        
    choice(
       choices: 'dev\nprod',
       description: 'choose deploy environment',
       name: 'p_deploy_env'
   )
   string (name: 'p_version', defaultValue: '1.0.0', description: 'build version')
 
   text (name: 'p_deploy_text', defaultValue: 'One\nTwo\nThree', description: '')

   password (name: 'p_password', defaultValue: '', description: '')
  }
}
