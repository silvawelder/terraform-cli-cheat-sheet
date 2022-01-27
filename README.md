# terraform-cli-cheat-sheet

### List all components (resouces, datasources, modules) in the tfstate file
 
```terraform state list```


### Remove a component (resouces, datasources, modules) in the tfstate file

```terraform state rm [options] <ADDRESS>```

### Destroy a component (resouces, datasources, modules)


```terraform destroy -target <ADDRESS>```

tip: get adresses references from de command ```terraform state list```
