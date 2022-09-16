# Implicit styles in App.xaml are applied too early, before the class's constructor

This sample project demonstrates a bug in .NET MAUI when declaring an implicit style in the application's resources. The status of the bug can be tracked from the following [.NET MAUI Bug Report](https://github.com/dotnet/maui/issues/10162).