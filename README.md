# Adevinta Spain SRE Challenge - CloudFormation

Nuestro Principal SRE se ha ido de vacaciones 🏖️ y ha dejado trabajo a medias ... 

Por suerte también ha dejado pistas:

Tenemos dos cloudformation stacks:
- [cloudformation-stack-1.yaml](cloudformation-stack-1.yaml) crea un AWS::ElasticLoadBalancingV2::TargetGroup
- [cloudformation-stack-2.yaml](cloudformation-stack-2.yaml) crea un AWS::ElasticLoadBalancingV2::LoadBalancer

necesitamos usar el TargetGroup del primero en el LoadBalancer del segundo 🤔
