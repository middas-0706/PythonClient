# AnnotationInfo


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
**title** | **StrictStr** | <em>the domain name or title of the quoted source</em> |[optional]|
**url** | **StrictStr** | <em>redirect URL to the quoted source</em><br>contains a Vertex AI redirect that leads to the original source |[optional]|
**direct_url** | **StrictStr** | <em>direct URL to the quoted source</em><br>contains the original source URL that the Vertex AI redirect in the `url` field leads to |[optional]|
**start_index** | **StrictInt** | <em>start of the annotation indexing</em> |[optional]|
**end_index** | **StrictInt** | <em>end of the annotation indexing</em> |[optional]|
**text** | **StrictStr** | <em>text of the reasoning chain section</em><br>text of the reasoning chain  section summarizing the model's thought process |[optional]|