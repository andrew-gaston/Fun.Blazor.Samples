GrpcDemo.Client is a WASM blazor app with Fun.Blazor which will consume the server by gRPC web client

GrpcDemo.Protos is a project which contains proto files, those files are shared between client and server. It is used for automatic code generation

GrpcDemo.Server is the server which provide gRPC web service


    dotnet run --project .\GrpcDemo.Client\GrpcDemo.Client.fsproj

    dotnet run --project .\GrpcDemo.Server\GrpcDemo.Server.fsproj