## install on a mac
    brew install dotnet-sdk
    brew cask install visual-studio-code
    brew install mysql@5.7
    brew services start mysql@5.7

## new project
    dotnet new web -n NetCoreApi -o netcoreapi
    cd !$
    dotnet new gitignore
    git init
    git add .
    git commit -m 'initial commit'
    git remote add origin https://github.com/tomthree/netcoreapi.git
    git push -u origin master
