# .NET Core ,  Docker , Docker compose and Cake build for Github Actions
 Docker image for GitHub action with dotnet core 2.2 , docker , docker compose and cake build global tools 

# Cake build action

```
action "cake action" {
  uses = "docker://iambipinpaul/dotnetdockercake:latest"  
  args = "dotnet cake build.cake"  
}
```
