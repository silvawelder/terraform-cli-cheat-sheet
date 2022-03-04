# terraform-cli-cheat-sheet

### List all components (resources, datasources, modules) in tfstate file
 
```terraform state list```


### Remove a component (resources, datasources, modules) in tfstate file

```terraform state rm [options] <ADDRESS>```

### Destroy a component (resources, datasources, modules)


```terraform destroy -target <ADDRESS>```

tip: get adresses references from command ```terraform state list```

### Plan a component (resources, datasources, modules)


```terraform plan -target <ADDRESS> -out plan-DDMMYYYY```

### Plan just to refresh tfstate definitions

```terraform plan -refresh-only -out plan-DDMMYYYY```
