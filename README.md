# ssh-sanar

ssh -f -N -L 127.0.0.1:4515:subscriptions-sanar-staging.editorasanar.com.br:80 -i migracao-esanar.pem ec2-user@ec2-35-174-81-113.compute-1.amazonaws.com && ssh -f -N -L 127.0.0.1:4514:coursesv2-sanar-staging.editorasanar.com.br:80 -i migracao-esanar.pem ec2-user@ec2-35-174-81-113.compute-1.amazonaws.com && ssh -f -N -L 127.0.0.1:4502:users-sanar-staging.editorasanar.com.br:80 -i migracao-esanar.pem ec2-user@ec2-35-174-81-113.compute-1.amazonaws.com && ssh -f -N -L 127.0.0.1:4501:residencia-sanar-staging.editorasanar.com.br:80 -i migracao-esanar.pem ec2-user@ec2-35-174-81-113.compute-1.amazonaws.com && ssh -f -N -L 127.0.0.1:4506:enrollments-sanar-staging.editorasanar.com.br:80 -i migracao-esanar.pem ec2-user@ec2-35-174-81-113.compute-1.amazonaws.com && ssh -f -N -L 127.0.0.1:4500:contents-sanar-staging.editorasanar.com.br:80 -i migracao-esanar.pem ec2-user@ec2-35-174-81-113.compute-1.amazonaws.com && ssh -f -N -L 127.0.0.1:4511:search-sanar-staging.editorasanar.com.br:80 -i migracao-esanar.pem ec2-user@ec2-35-174-81-113.compute-1.amazonaws.com


### new machine 11/12/2019: ec2-3-93-42-119.compute-1.amazonaws.com
### new machine 11/12/2019: ec2-35-174-81-113.compute-1.amazonaws.com

