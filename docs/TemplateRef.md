

# TemplateRef

TemplateRef is a reference of template resource.
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**clusterScope** | **Boolean** | ClusterScope indicates the referred template is cluster scoped (i.e. a ClusterWorkflowTemplate). |  [optional]
**name** | **String** | Name is the resource name of the template. |  [optional]
**runtimeResolution** | **Boolean** | RuntimeResolution skips validation at creation time. By enabling this option, you can create the referred workflow template before the actual runtime. DEPRECATED: This value is not used anymore and is ignored |  [optional]
**template** | **String** | Template is the name of referred template in the resource. |  [optional]



