# Use official Azure Functions base image for .NET 8 isolated
FROM mcr.microsoft.com/azure-functions/dotnet-isolated:4-dotnet-isolated8.0-appservice
# Set working directory inside container
WORKDIR /home/site/wwwroot
# Copy function files into the container
COPY . .