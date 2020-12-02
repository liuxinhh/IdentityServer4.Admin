FROM swr.cn-south-1.myhuaweicloud.com/mcr/aspnet:3.1-alpine 
WORKDIR /app
COPY . . 
EXPOSE 44310
ENTRYPOINT ["dotnet", "Skoruba.IdentityServer4.STS.Identity.dll","-b","0.0.0.0"]