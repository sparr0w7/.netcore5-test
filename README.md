# .netcore5-test
.netcore5 test

# vscode 프로젝트 생성
```bash
dotnet new webapi -o TodoApi
cd TodoApi
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.InMemory
code -r ../TodoApi
```
# vscode 실행
control + F5
