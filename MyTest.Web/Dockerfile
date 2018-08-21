FROM microsoft/aspnetcore:2.0
WORKDIR /app
COPY . /app
RUN dotnet restore
EXPOSE 8008
ENV ASPNETCORE_URLS http://*:8008
ENTRYPOINT ["dotnet","run"]
