FROM varsitycalvinballteamcaptain/docknet

USER root

WORKDIR /app

ENV ASPNETCORE_ENVIRONMENT="Development"
ENV ASPNETCORE_HTTP_PORTS=5010
EXPOSE 5010:5010

ENTRYPOINT [ "dotnet", "docknet.dll" ]