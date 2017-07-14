# config:export:single
Exportar uma configuração única como um arquivo YML.

**application.gitbook.messages.usage:**
```
drupal config:export:single [options]
ces
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--name | commands.config.export.single.options.name
--directory | Escolha o diretório onde a configuração exportada será salva.
--module | O nome do módulo.
--include-dependencies | Export dependencies of the configuration as well.
--optional | Export config as an optional YAML configuration in your module
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## application.gitbook.messages.examples
* Provide config settings name to be exported
```
drupal config:export:single \
  --name=config.settings.name
```
* if uuid and/or config hashes will be removed.
```
drupal config:export:single \
  --name=config.settings.name \
  --remove-uuid \
  --remove-config-hash
```