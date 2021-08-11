# be.rufer.CS.Examples.Blazor.Webassembly
Playing around with Blazor Webassembly

## Important notes

> Razor component file names require a capitalized first letter. 

> For URLs to resolve correctly, the app must include a <base> tag in its wwwroot/index.html file (Blazor WebAssembly) or Pages/_Host.cshtml file (Blazor Server) with the app base path specified in the href attribute.

> Configuration and settings files in a Blazor WebAssembly app are visible to users. Don't store app secrets, credentials, or any other sensitive data in the configuration or files of a Blazor WebAssembly app.

> Blazor WebAssembly apps don't currently have a concept of DI scopes. Scoped-registered services behave like Singleton services.

> Providing initial values for component parameters is supported, but don't create a component that writes to its own parameters after the component is rendered for the first time.

## Useful links
- [Blazor official website](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
- [Blazor official doc](https://docs.microsoft.com/en-us/aspnet/core/blazor/?view=aspnetcore-5.0)
- [Blazor tutorial](https://dotnet.microsoft.com/learn/aspnet/blazor-tutorial/intro)
- [Awesome Blazor](https://github.com/AdrienTorris/awesome-blazor)
- [MS Docs - Build a web app with Blazor](https://docs.microsoft.com/en-us/learn/modules/build-blazor-webassembly-visual-studio-code/)
