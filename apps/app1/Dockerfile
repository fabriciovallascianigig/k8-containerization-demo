<<<<<<< HEAD
# apps/app1/
=======
>>>>>>> origin/main
# Use the official Microsoft .NET runtime image as the base image
FROM mcr.microsoft.com/dotnet/aspnet:7.0

# Set the working directory inside the container
WORKDIR /app

# Copy the published output of the application to the container
COPY ./publish /app

<<<<<<< HEAD
# Set the environment of the app to development so that swagger works
ENV ASPNETCORE_ENVIRONMENT=Development

=======
>>>>>>> origin/main
# Set the port the application will listen on
ENV ASPNETCORE_URLS=http://+:8080

# Expose the port the application will run on
EXPOSE 8080

# Start the application using the dotnet runtime
ENTRYPOINT ["dotnet", "app1.dll"]