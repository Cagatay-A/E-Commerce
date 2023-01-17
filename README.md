# E-Commerce
Simple E Commerce(ASP.NET Core Mvc + Angular + MsSql + Redis + Stripe)

Click expand here.

install chocolatey: https://chocolatey.org/install

Enter the code to power Shell: Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

For version checking ; https://community.chocolatey.org/packages/redis-64#versionhistory

install redis: example: "choco install redis-64 --version=3.0.503"

Add Db: Go to "\DBs" And add "StoreDatabase.mdf" to Sql server

Run CLI: redis-server and redis-cli go to "\src\client" and enter to power shell --> "npm i -f" and "ng serve"

Run API: Go to "\src" And write to "dotnet build" and "dotnet run"(in another shell) in power shell.

TEST:
user@outlook.com
Root-123
