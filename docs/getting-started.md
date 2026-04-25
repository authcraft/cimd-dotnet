# Getting Started

## Build

```bash
dotnet build AuthCraft.Cimd.sln --configuration Release
```

## Test

```bash
# Run all tests
dotnet test AuthCraft.Cimd.sln --configuration Release --no-build --verbosity normal

# Run a specific test class
dotnet test AuthCraft.Cimd.sln --filter "FullyQualifiedName~ClientIdentifierValidatorTests"
```

## Format

```bash
dotnet format AuthCraft.Cimd.sln
```