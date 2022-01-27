# terraform-cli-cheat-sheet

### List all components (resources, datasources, modules) in the tfstate file
 
```terraform state list```


### Remove a component (resources, datasources, modules) in the tfstate file

```terraform state rm [options] <ADDRESS>```

### Destroy a component (resources, datasources, modules)


```terraform destroy -target <ADDRESS>```

tip: get adresses references from de command ```terraform state list```
