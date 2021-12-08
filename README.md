# Cloud-run-FastAPI-demo
for personal reference


```
gcloud config set run/region asia-southeast1
gcloud builds submit --tag gcr.io/sue-gcp-learn/cloud-run-demo
gcloud run deploy --image gcr.io/sue-gcp-learn/cloud-run-demo --platform managed
```
