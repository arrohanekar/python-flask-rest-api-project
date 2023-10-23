## 1. Build Docker image 
```commandline
docker build -t python-rest-api .
```

## 2. Run Docker image
```commandline
docker run -p 9001:9001 python-rest-api
```



## 3. User and follow the below 

https://jhooq.com/getting-start-with-helm-chart/


helloworld
├── charts
├── **Chart.yaml**
├── templates
│  ├── deployment.yaml
│  ├── _helpers.tpl
│  ├── hpa.yaml
│  ├── ingress.yaml
│  ├── NOTES.txt
│  ├── serviceaccount.yaml
│  ├── service.yaml
│  └── tests
│      └── test-connection.yaml
└── **values.yaml**
