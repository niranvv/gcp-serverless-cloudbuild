# gcp-serverless-cloudbuild
Test Node Application to automatically build &amp; deploy to Google Cloud Serverless Services

## Build & Test locally
```
cd node-hello-world
npm install
npm start
```

## Enable APIs
```
gcloud services enable appengine.googleapis.com cloudfunctions.googleapis.com artifactregistry.googleapis.com run.googleapis.com translate.googleapis.com
```

## App Engine Deploy
```
gcloud app deploy
```

## Cloud Run Deploy
```
gcloud run deploy
```