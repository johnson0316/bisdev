FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
EXPOSE 8008
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "MyTest.Web.dll"]
