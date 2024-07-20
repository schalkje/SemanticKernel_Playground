
# Semantic Kernal

First app

## secret management
https://github.com/microsoft/semantic-kernel/tree/main/dotnet/samples/GettingStarted

```
cd dotnet/samples/Concepts

dotnet user-secrets init

dotnet user-secrets set "OpenAI:ModelId" "..."
dotnet user-secrets set "OpenAI:ChatModelId" "..."
dotnet user-secrets set "OpenAI:EmbeddingModelId" "..."
dotnet user-secrets set "OpenAI:ApiKey" "..."
```

Most of the examples will require secrets and credentials, to access OpenAI, Azure OpenAI, Bing and other resources. We suggest using .NET Secret Manager to avoid the risk of leaking secrets into the repository, branches and pull requests. You can also use environment variables if you prefer.

# OpenAI
OpenAI__ModelId
OpenAI__ChatModelId
OpenAI__EmbeddingModelId
OpenAI__ApiKey