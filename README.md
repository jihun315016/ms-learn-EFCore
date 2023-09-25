# ms-learn-EFCore
- EF Core 학습을 위한 저장소  
- Microsoft에서 제공하는 [Entity Framework Core를 사용하여 관계형 데이터 유지 및 검색](https://learn.microsoft.com/ko-kr/training/modules/persist-data-ef-core/)을 참고한다.  


# .NET CLI
```bash
dotnet ef migrations add InitialCreate --context PizzaContext
```
PizzaContext 클래스를 기반으로 InitialCreate 이름의 Migration 파일을 생성한다.

```bash
dotnet ef database update --context PizzaContext
```
PizzaContext 클래스와 같은 형태로 실제 데이터베이스에 적용한다.
