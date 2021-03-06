<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-core-server](./kibana-plugin-core-server.md) &gt; [SavedObjectsCreateOptions](./kibana-plugin-core-server.savedobjectscreateoptions.md)

## SavedObjectsCreateOptions interface


<b>Signature:</b>

```typescript
export interface SavedObjectsCreateOptions extends SavedObjectsBaseOptions 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [id](./kibana-plugin-core-server.savedobjectscreateoptions.id.md) | <code>string</code> | (not recommended) Specify an id for the document |
|  [migrationVersion](./kibana-plugin-core-server.savedobjectscreateoptions.migrationversion.md) | <code>SavedObjectsMigrationVersion</code> | Information about the migrations that have been applied to this SavedObject. When Kibana starts up, KibanaMigrator detects outdated documents and migrates them based on this value. For each migration that has been applied, the plugin's name is used as a key and the latest migration version as the value. |
|  [namespaces](./kibana-plugin-core-server.savedobjectscreateoptions.namespaces.md) | <code>string[]</code> | Optional initial namespaces for the object to be created in. If this is defined, it will supersede the namespace ID that is in [SavedObjectsCreateOptions](./kibana-plugin-core-server.savedobjectscreateoptions.md)<!-- -->.<!-- -->Note: this can only be used for multi-namespace object types. |
|  [originId](./kibana-plugin-core-server.savedobjectscreateoptions.originid.md) | <code>string</code> | Optional ID of the original saved object, if this object's <code>id</code> was regenerated |
|  [overwrite](./kibana-plugin-core-server.savedobjectscreateoptions.overwrite.md) | <code>boolean</code> | Overwrite existing documents (defaults to false) |
|  [references](./kibana-plugin-core-server.savedobjectscreateoptions.references.md) | <code>SavedObjectReference[]</code> |  |
|  [refresh](./kibana-plugin-core-server.savedobjectscreateoptions.refresh.md) | <code>MutatingOperationRefreshSetting</code> | The Elasticsearch Refresh setting for this operation |
|  [version](./kibana-plugin-core-server.savedobjectscreateoptions.version.md) | <code>string</code> | An opaque version number which changes on each successful write operation. Can be used in conjunction with <code>overwrite</code> for implementing optimistic concurrency control. |

