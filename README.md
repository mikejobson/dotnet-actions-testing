# Test Library

This package is just for CI and publish testing only. Do not use! 🙂

[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/mikejobson/dotnet-actions-testing/test.yml?branch=main&style=flat&logo=github&label=status)](https://github.com/mikejobson/dotnet-actions-testing/actions)
[![GitHub Issues](https://img.shields.io/github/issues/mikejobson/dotnet-actions-testing?style=flat&logo=github)](https://github.com/mikejobson/dotnet-actions-testing/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/mikejobson/dotnet-actions-testing?style=flat&logo=github)](https://github.com/mikejobson/dotnet-actions-testing/pulls)
[![NuGet Version](https://img.shields.io/nuget/v/UXAV.TestLib?style=flat&logo=nuget&link=https%3A%2F%2Fwww.nuget.org%2Fpackages%2FUXAV.TestLib)](https://www.nuget.org/packages/UXAV.TestLib)
[![NuGet Downloads](https://img.shields.io/nuget/dt/UXAV.TestLib?style=flat&logo=nuget)](https://www.nuget.org/packages/UXAV.TestLib)
[![GitHub License](https://img.shields.io/github/license/mikejobson/dotnet-actions-testing?style=flat)](LICENSE)

## Links

GitHub Repository: [dotnet-actions-testing](https://github.com/mikejobson/dotnet-actions-testing)

NuGet Package: [UXAV.TestLib](https://www.nuget.org/packages/UXAV.TestLib/)

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.

Please ensure that your code follows the project's coding conventions and includes appropriate tests.

- For feature branches use the name `feature/feature-name`
- Version numbers are checked against existing tags and fail CI on match

Thank you for your interest in contributing to this project!

## Usage

To use this test library in your project, follow these steps:

1. Install the package via NuGet. You can use the following command in the Package Manager Console:

   ```
    dotnet add [<PROJECT>] package UXAV.TestLib
   ```

2. Import the library in your code file:

   ```csharp
   using UXAV.TestLib;
   ```

3. Start using the library's features in your code:
   ```csharp
   var testLib = new TestLibrary();
   testLib.DoSomething();
   ```

## Documentation

Add documentation here

## License

This project is licensed under the [MIT License](LICENSE).
