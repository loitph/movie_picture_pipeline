# Movie Picture Pipeline

Please following step below to finish:

1. Create .github/workflows and files Front-end, Back-end CI/CD

2. Login to AWS

3. Create Cluster Role

4. Create Cluster

5. Create Node Group Role: AmazonEC2ContainerRegistryReadOnly, AmazonEKS_CNI_Policy, AmazonEKSWorkerNodePolicy

6. Chose Node Group AMI type: Amazon Linux 2 (AL2_x86_64), c3.large(2 CPUs, 8gb)

7. Create ECR repositories: movie-picture-be, movie-picture-fe

8. Create Repo github, push with secrets:
AWS_ACCESS_KEY_ID,
AWS_ACCOUNT_ID,
AWS_REGION,
AWS_SECRET_ACCESS_KEY,
AWS_SESSION_TOKEN,
REACT_APP_MOVIE_API_URL.

9. Run github action

10. Result:
http://adc21cb94c99f4566b21590a3feb5c64-614442379.us-east-1.elb.amazonaws.com/movies
http://a837a59bd110940f8b219a77c40376c6-1974362163.us-east-1.elb.amazonaws.com/
