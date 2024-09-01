---
title: "ASP.NET Core docs: What's new for August 1, 2024 - August 31, 2024"
description: "What's new in the ASP.NET Core docs for August 1, 2024 - August 31, 2024."
ms.date: 09/01/2024
---

# ASP.NET Core docs: What's new for August 1, 2024 - August 31, 2024

Welcome to what's new in the ASP.NET Core docs from August 1, 2024 through August 31, 2024. This article lists some of the major changes to docs during this period.

## Blazor

### New articles

- <xref:blazor/security/webassembly/meid-groups-roles-net5to7>
- <xref:blazor/tutorials/movie-database-app/index>
- <xref:blazor/tutorials/movie-database-app/part-1>
- <xref:blazor/tutorials/movie-database-app/part-2>
- <xref:blazor/tutorials/movie-database-app/part-3>
- <xref:blazor/tutorials/movie-database-app/part-4>
- <xref:blazor/tutorials/movie-database-app/part-5>
- <xref:blazor/tutorials/movie-database-app/part-6>
- <xref:blazor/tutorials/movie-database-app/part-7>
- <xref:blazor/tutorials/movie-database-app/part-8>

### Updated articles

- <xref:blazor/forms/binding>
  - [Blazor] Forms - Binding - Custom input components - InputBase recommendation
  - [Blazor] Binding - Custom input components - naming of demo components
  - Make [SupplyParameterFrom{X}] props private
  - Custom input components
- <xref:blazor/fundamentals/signalr>
  - Use "session affinity" terminology
  - Cover workaround for AmbiguousMatchException
- <xref:blazor/security/server/qrcodes-for-authenticator-apps>
  - Improve site (company) name setting coverage
  - Add TOTP security warning
- <xref:blazor/images-and-documents>
  - Promote NOTE to article text
  - Expand images coverage to include documents
- <xref:blazor/components/quickgrid>
  - Blazor scaffolder VS location change
  - Change paginator remark
- <xref:blazor/tooling>
  - fix typo (WebAssmebly -> WebAssembly)
  - Hosted WASM project for SDK 8.0 or later
- <xref:blazor/components/dynamiccomponent> - Add section for DynamicComponent Instance property
- <xref:blazor/components/rendering> - Clarify how StateHasChanged works
- <xref:blazor/fundamentals/routing> - Make [SupplyParameterFrom{X}] props private
- <xref:blazor/security/server/index>
  - Authentication state management at sign out
  - Improve custom auth service provider
- <xref:blazor/security/webassembly/meid-groups-roles>
  - Blazor ME-ID Groups & Roles article updates
  - Add roles/groups coverage to the BWA+OIDC article
- <xref:blazor/project-structure> - Improve BWA project structure coverage
- <xref:blazor/fundamentals/index> - Swap section order
- <xref:blazor/performance>
  - Add NOTE on error boundary support
  - Add timezone code/data control coverage
- <xref:blazor/file-uploads> - File uploads (writing to memory/Autofac content)
- <xref:blazor/js-interop/index>
  - Class field of type function not supported
  - Refactor JS event handler examples
- <xref:blazor/components/js-spa-frameworks>
  - Refactor JS event handler examples
  - Drop BWA coverage from JS-SPA article
- <xref:blazor/js-interop/call-dotnet-from-javascript> - Refactor JS event handler examples
- <xref:blazor/globalization-localization> - Add timezone code/data control coverage
- <xref:blazor/forms/index> - Enhance Blazor forms validation coverage
- <xref:blazor/forms/validation> - Enhance Blazor forms validation coverage
- <xref:blazor/security/blazor-web-app-oidc> - Add roles/groups coverage to the BWA+OIDC article
- <xref:blazor/js-interop/import-export-interop> - Enhanced JSImport/JSExport guidance
- <xref:blazor/call-web-api> - Add new Blazor tutorial on BWA with EF Core

## Client-side development

### New articles

- <xref:client-side/dotnet-interop/index>
- <xref:client-side/dotnet-interop/wasm-browser-app>

### Updated articles

- <xref:client-side/dotnet-interop> - Enhanced JSImport/JSExport guidance

## Fundamentals

### New articles

- <xref:fundamentals/openapi/aspnetcore-openapi>
- <xref:fundamentals/openapi/overview>
- <xref:fundamentals/openapi/openapi-tools>

### Updated articles

- <xref:fundamentals/host/generic-host> - Clarify meaning of {PREFIX}_HTTPS_PORTS vs. _PORT
- <xref:fundamentals/host/web-host> - Clarify meaning of {PREFIX}_HTTPS_PORTS vs. _PORT
- <xref:fundamentals/openapi/aspnetcore-openapi>
  - Improvements to transformer registration APIs in Microsoft.AspNetCore.OpenApi
  - Follow-up to #33266
  - Restructure and update OpenAPI doc
- <xref:fundamentals/error-handling> - Add option to ExceptionHandlerMiddleware to choose status code based on exception
- <xref:fundamentals/native-aot>
  - Update native-aot.md
  - AOT Mon prep
- <xref:fundamentals/openapi/overview>
  - Follow-up to #33266
  - Restructure and update OpenAPI doc
- <xref:fundamentals/portable-object-localization> - Add plural localization examples for additional arguments
- <xref:fundamentals/openapi/openapi-tools>
  - Restructure OpenAPI toc.yml section
  - Restructure and update OpenAPI doc
- <xref:fundamentals/index> - Prep article for a .NET 8 moniker section

## Migration

### Updated articles

- <xref:migration/20_21> - RCL casing

## MVC

### Updated articles

- <xref:mvc/views/view-compilation> - RCL casing
- <xref:mvc/models/file-uploads> - Fix typo

## Release notes

### Updated articles

- <xref:aspnetcore-9>
  - Update WN9 include links
  - What's New: SignalR: Adding include file
  - Add new features to What's new

## Security

### Updated articles

- <xref:security/authentication/customize_identity_model> - RCL casing
- <xref:security/enforcing-ssl>
  - Clarify meaning of {PREFIX}_HTTPS_PORTS vs. _PORT
  - Revert "Update Linux dev cert trust instructions"
  - Update Linux dev cert trust instructions
- <xref:security/docker-compose-https> - mon prep
- <xref:security/docker-https> - Mon prep/docker/certs
- <xref:security/authentication/identity-enable-qrcodes> - Document that TOTP codes can be reused before it expires
- <xref:security/authentication/claims> - .NET 9: OpenIdConnectHandler adds support for Pushed Authorization Requests (PAR)
- <xref:security/data-protection/configuration/default-settings>
  - delete keys
  - moniker prep

## Tutorials

### Updated articles

- <xref:tutorials/first-web-api> - First Web API: Update prep for 8.0 & 9.0
- <xref:tutorials/razor-pages/razor-pages-start> - RP Add Model: Remove warning and Update VSC Instruction

## Community contributors

The following people contributed to the ASP.NET Core docs during this period. Thank you! Learn how to contribute by following the links under "Get involved" in the [what's new landing page](index.yml).

- [guardrex](https://github.com/guardrex) - Luke Latham (41)
- [tdykstra](https://github.com/tdykstra) - Tom Dykstra (18)
- [wadepickett](https://github.com/wadepickett) - Wade Pickett (11)
- [adegeo](https://github.com/adegeo) - Andy (Steve) De George (3)
- [hakenr](https://github.com/hakenr) - Robert Haken (3)
- [Kissaki](https://github.com/Kissaki) - Jan Klass (2)
- [aleksvujic](https://github.com/aleksvujic) - Aleks Vujić (1)
- [Alexanderbtw](https://github.com/Alexanderbtw) - Alexander (1)
- [alexravenna](https://github.com/alexravenna) - Alex Ravenna (1)
- [damienbod](https://github.com/damienbod) - damienbod (1)
- [hliyan](https://github.com/hliyan) - Hasitha N. Liyanage (1)
- [jaliyaudagedara](https://github.com/jaliyaudagedara) - Jaliya Udagedara (1)
- [kevinchalet](https://github.com/kevinchalet) - Kévin Chalet (1)
- [mrkaarel](https://github.com/mrkaarel) - Kaarel (1)
- [pollyndos](https://github.com/pollyndos) (1)
- [ryan-carbon](https://github.com/ryan-carbon) (1)
- [SuleymanCommits](https://github.com/SuleymanCommits) - Suleyman (1)
- [tgondar](https://github.com/tgondar) - Telmo Gondar (1)
- [udidahan](https://github.com/udidahan) - Udi Dahan (1)
- [v-emilypr](https://github.com/v-emilypr) - Emily Prindeville  (1)
- [wenz](https://github.com/wenz) - Christian Wenz (1)
