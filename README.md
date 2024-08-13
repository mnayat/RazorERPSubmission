Tech Stach : .net core 6, mapster , efcore
Pattern : cqrs, mediatr

in case of migration 
Add-Migration InitialCreate -Context ApplicationDBContext -OutputDir RazorCompany.Infrastructure\Persistence\Migrations -Namespace RazorCompany.Infrastructure.Persistence.Migrations   -Project RazorCompany.Infrastructure -StartupProject RazorCompanyAPI
