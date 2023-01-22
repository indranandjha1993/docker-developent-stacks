FROM mcr.microsoft.com/dotnet/core/sdk:latest

COPY src/ /c#

WORKDIR /c#

RUN dotnet build

CMD ["dotnet", "run"]
