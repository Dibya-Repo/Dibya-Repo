Requesting access to Kubernetes Cluster
Overview
This document provides guidance on requesting access to Kubernetes cluster using Apono Portal https://portal.apono.io/ 
Access to the Kubernetes Cluster is granted based on Integration Request which includes Integration, Resource type, Resources and Permissions.

Prerequisites:
Before requesting Access, ensure that you have completed the following:
1.	Installed and configured kubectl CLI. 
“Kubectl” is a command-line tool that allows you  to interact with Kubernetes Cluster.
Refer https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/ for Linux and https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/ for Windows.
2.	Obtained necessary approvals from your manager or Lead.

Access request process:
Open https://portal.apono.io/ and you will get an interface like:
![Home-Apono](https://github.com/Dibya-Repo/Test/assets/150330887/f9f2f898-9512-4d49-9c9b-67685d5925f4)

Click on "New Request" 
![New Request](https://github.com/Dibya-Repo/Test/assets/150330887/3f5e9c54-6e77-4d0a-92b4-53ca0ffafcad)

For "New Request", go to "Integration Request" and Select the desired Intgration from the drop down list as below:
![Integration](https://github.com/Dibya-Repo/Test/assets/150330887/e8312603-15fb-43ed-8aab-40c57f7ed26e)

For "Resource type", select Cluster from the dropdown list as below:
![Resource Type](https://github.com/Dibya-Repo/Test/assets/150330887/d51618f7-32ca-48b4-8c96-3bba4d817460)

For "Resources", Click the dropdown list and mark the checkbox for the available resource as below:
![Resources](https://github.com/Dibya-Repo/Test/assets/150330887/88268353-b376-45b9-ba31-ca2eec125193)

For "Permissions", check the checkbox Cluster-Admin available under the dropdown list as below:
![Permissions](https://github.com/Dibya-Repo/Test/assets/150330887/98be2849-5f17-45f6-b19d-adbe500316a6)

Under "Justification", add a justification as per the required access and click on "Request".
![Justification](https://github.com/Dibya-Repo/Test/assets/150330887/f9d7936f-b623-4d05-904a-e0fafd4f96f1)

Go to "My Requests" and click on "View access details" for the newly created cluster access as below:
![View Access Datails](https://github.com/Dibya-Repo/Test/assets/150330887/9fb0b437-1141-4d06-9bbf-0d391e4fd434)

You will get few kubectl config commands and you need to copy those commands and save in a separate directory locally:
![kubeconfig-detail](https://github.com/Dibya-Repo/Test/assets/150330887/63035f1b-214a-4814-9bfa-b3bc83c6ff29)

Use the above kubectl config commands using the respective context as below:
![config](https://github.com/Dibya-Repo/Test/assets/150330887/6c4ce20e-f779-4639-9eb6-56240c0616df)






