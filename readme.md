Core utilities for OpenGET C# that are NOT tied to Unity.
This is meant to be compiled as a standalone DLL, but you can import the scripts directly into Unity.

To enable experimental .NET 6 features, please define the conditional OPENGET_DOTNET6.
This is required for the following features to be enabled:
- Interpolated string localisation

Please note that these experimental features are NOT guaranteed to work on all platforms for Unity versions that do not support .NET 6 or above
(i.e. all Unity versions at time of writing), especially as this uses the newer System.Runtime DLL.
