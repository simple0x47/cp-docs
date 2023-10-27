# .csproj order

1. `ItemGroup` containing folders.
2. `ItemGroup` containing local references.
3. `ItemGroup` containing Cuplan references.
4. `ItemGroup` containing third party references.

# Tests

## Naming convention

The naming of tests must be the following one:
`FunctionTested`_`WithKindOfArguments`_`ExpectedResult`

For example: `CreateMember_WithNonExistingOrgId_Fails`