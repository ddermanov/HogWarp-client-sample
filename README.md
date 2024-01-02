# Example client side mod for HogWarp

To get this working, first install the [UE project for HL](https://github.com/narknon/PhoenixUProj).

Once you have this installed, just copy and paste the Content directory from this repository to your UE project.

You will need to assign a unique chunk id to the Content/HogWarp/Example asset, see [this tutorial](https://modding.wiki/en/hogwartslegacy/developers/getting-started).

Once you have packaged the project, rename the files associated with the chunk id you picked to `Example` so you have Example.ucas, Example.utoc, Example.pak, and move these files in the Mods folder in your HogWarp install.

In order to prevent errors when packaging while following the [UE project for HL](https://github.com/narknon/PhoenixUProj) guide on installation, you will need to manually build the AutomationTool via Visual Studio 22 or equivalent flavour by going to UE4.sln opening it with the Visual Studio 22 or equivalent tool of your choice, navigating to Solution Explorer -> AutomationTool -> Build
