# dataviz_projects
## dwapi
```R
Sys.setenv(DW_USER = "avershinina")
Sys.setenv(DW_AUTH_TOKEN = "TOKEN")
cars_dataset <- dwapi::create_dataset(Sys.getenv("DW_USER"), create_cars_dataset)
cars_dataset
```
