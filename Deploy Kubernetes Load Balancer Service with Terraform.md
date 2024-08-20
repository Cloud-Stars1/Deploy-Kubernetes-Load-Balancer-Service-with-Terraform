# Deploy Kubernetes Load Balancer Service with Terraform || GSP233

## Solution [here](https://youtu.be/xnKyLnHcBXU)

### Run the following Commands in the Cloud shell


```
export ZONE=
```

```
gcloud auth list

export REGION="${ZONE%-*}"

gsutil -m cp -r gs://spls/gsp233/* .

cd tf-gke-k8s-service-lb

terraform init

terraform apply -var="region=$REGION" -var="location=$ZONE" --auto-approve
```



### Congratulations 🎉 for completing the Lab !

##### You Have Successfully Demonstrated Your Skills And Determination.

#### *Well done!*

#### Don't Forget to Join the [Telegram Channel](https://t.me/cloudstars24)

### Subscribe to our YouTube Channel [CLOUD STARS](https://www.youtube.com/@cloud-stars)
