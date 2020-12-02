FROM swr.cn-south-1.myhuaweicloud.com/mcr/aspnet:3.1-alpine 
WORKDIR /app
COPY . . 
EXPOSE 44303
ENTRYPOINT ["dotnet", "Skoruba.IdentityServer4.Admin.Api.dll","-b","0.0.0.0"]