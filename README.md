Read me

    ami-0b043d7dc31a5fba6
Technologies

         -Docker
         -Minikube 
         -Eksctl
         -Flux
    
Deployment        
https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#AMICatalog:

        Go to "My AMIs" and search for "ami-0b043d7dc31a5fba6"  => Lunch Instance with AMI
        
        K8s 
        This application can be easily deployed using minikube
            "$ minikube start" to start K8s-lockal engine
        Eksctl
            For using EKS cluster you will need an user with EkS "AmazonEKSClusterPolicy" & "AmazoneEKSWorkerNodePolicy" attachted to it.

            Run "$ aws configure" to set the EKS-user-Creditails.

TEKTON-FLUX-PIPELINE

    
ami-0f2ccf6c89812b5c3

    Technologies    

        -Docker
        -Minikube
        -Eksctl
        -Flux
        -Tekton
    
Deployment
https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#AMICatalog:

        Go to "Community AMIs" and search for "ami-0f2ccf6c89812b5c3"  => Lunch Instance with AMI

https://github.com/mmehrazar/my-repo.git
        

        
