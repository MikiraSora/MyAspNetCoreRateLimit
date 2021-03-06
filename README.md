AspNetCoreRateLimit
==============

**Notice:此插件仅用于自己网站功能，可能会比原repo删除些许功能以及添加功能.    --by MikiraSora**

AspNetCoreRateLimit is an ASP.NET Core rate limiting solution designed to control the rate of requests that clients can make to a Web API or MVC app based on IP address or client ID. The [AspNetCoreRateLimit package](https://www.nuget.org/packages/AspNetCoreRateLimit/) contains an IpRateLimitMiddleware and a ClientRateLimitMiddleware, with each middleware you can set multiple limits for different scenarios like allowing an IP or Client to make a maximum number of calls in a time interval like per second, 15 minutes, etc. You can define these limits to address all requests made to an API or you can scope the limits to each API URL or HTTP verb and path.

[![Build status](https://ci.appveyor.com/api/projects/status/jrfxft7anqckn30s?svg=true)](https://ci.appveyor.com/project/stefanprodan/AspNetCoreRateLimit)
[![NuGet](https://img.shields.io/nuget/v/AspNetCoreRateLimit.svg?maxAge=259200)](https://www.nuget.org/packages/AspNetCoreRateLimit/) 

**Documentation**

Rate limiting based on client IP

- [Setup and configuration](https://github.com/stefanprodan/AspNetCoreRateLimit/wiki/IpRateLimitMiddleware#setup)
- [Defining rate limit rules](https://github.com/stefanprodan/AspNetCoreRateLimit/wiki/IpRateLimitMiddleware#defining-rate-limit-rules)
- [Behavior](https://github.com/stefanprodan/AspNetCoreRateLimit/wiki/IpRateLimitMiddleware#behavior)
- [Update rate limits at runtime](https://github.com/stefanprodan/AspNetCoreRateLimit/wiki/IpRateLimitMiddleware#update-rate-limits-at-runtime)

Rate limiting based on client ID

- [Setup and configuration](https://github.com/stefanprodan/AspNetCoreRateLimit/wiki/ClientRateLimitMiddleware#setup)
- [Defining rate limit rules](https://github.com/stefanprodan/AspNetCoreRateLimit/wiki/ClientRateLimitMiddleware#defining-rate-limit-rules)
- [Behavior](https://github.com/stefanprodan/AspNetCoreRateLimit/wiki/ClientRateLimitMiddleware#behavior)
- [Update rate limits at runtime](https://github.com/stefanprodan/AspNetCoreRateLimit/wiki/ClientRateLimitMiddleware#update-rate-limits-at-runtime)
