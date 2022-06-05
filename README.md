Use [mason](https://pub.dev/packages/mason_cli) to generate HelloWorld template.

Easier than the [official steps](https://www.spigotmc.org/wiki/creating-a-blank-spigot-plugin-in-vs-code/).

```
mason add -g minecraft_spigot --git-url https://github.com/Tokenyet/SpigotPluginTemplate
mason get
mason make minecraft_spigot
```

Then, You should set env properyly at .vscode/settings.json, such as maven, java...

The final steps to generate plugin.jar.

```
mvn install
```
