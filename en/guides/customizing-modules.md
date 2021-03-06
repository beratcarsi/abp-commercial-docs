# Customizing the Modules

This guide has references to related documents those explain **how to customize a depended [application module](../modules/index.md)** when you want to use the module as **NuGet/NPM package references**.

## ABP Framework Infrastructure

ABP Framework already provides many different approaches to **extend or customize** a depended module. See the "**[Customizing the Application Modules](https://docs.abp.io/en/abp/latest/Customizing-Application-Modules-Guide)**" guide as the **fundamental reference**.

## ABP Commercial Infrastructure

ABP Commercial adds **more extension points** on top of the ABP Framework.

> This section **only focuses on the additional features** provided by the ABP Commercial. You should definitely see the guide mentioned in the previous section.

### Entity Actions

Entity action extension system allows you to add a new action to the action menu for an entity. A "Click Me" action was added to the user management page below:

![user-action-extension-click-me](../images/user-action-extension-click-me.png)

You can take **any action** (open a modal, make an HTTP API call, redirect to another page... etc) by writing your **custom code**. You can access to the **current entity** in your code.

See the related documents to learn how to use this system:

* [Entity Action Extensions for ASP.NET Core UI](../ui/aspnetcore/entity-action-extensions.md)
* [Entity Action Extensions for Angular](../ui/angular/entity-action-extensions.md)