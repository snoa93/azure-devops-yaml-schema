---
title: variables.template definition
description: variables.template definition reference.
ms.date: 01/18/2023
monikerRange: "= azure-pipelines || = azure-pipelines-2019 || = azure-pipelines-2019.1 || = azure-pipelines-2020 || = azure-pipelines-2020.1 || = azure-pipelines-2022"
---

# variables.template definition


You can define a set of variables in one file and use it multiple times in other files.


:::moniker range="= azure-pipelines-2019"

<!-- :::api-definition signature="variable{template}" version="azure-pipelines-2019"::: -->

```yaml
variables:
- template: string # Required as first property. Template file with variables.. 
  parameters:  # Parameters to map into a the template.
    string: string # Name/value pairs.
```


Properties that use this definition: [variables.](variables.md)

## Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `template`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Required as first parameter. Template file with variables. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `parameters`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string name/value pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Parameters to map into a the template. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines-2019.1"

<!-- :::api-definition signature="variable{template}" version="azure-pipelines-2019.1"::: -->

```yaml
variables:
- template: string # Required as first property. Template file with variables.. 
  parameters:  # Parameters to map into a the template.
    string: string # Name/value pairs.
```


Properties that use this definition: [variables.](variables.md)

## Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `template`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Required as first parameter. Template file with variables. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `parameters`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string name/value pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Parameters to map into a the template. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines-2020"

<!-- :::api-definition signature="variable{template}" version="azure-pipelines-2020"::: -->

```yaml
variables:
- template: string # Required as first property. Template file with variables.. 
  parameters:  # Parameters to map into a the template.
    string: string # Name/value pairs.
```


Properties that use this definition: [variables.](variables.md)

## Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `template`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Required as first parameter. Template file with variables. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `parameters`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string name/value pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Parameters to map into a the template. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines-2020.1"

<!-- :::api-definition signature="variable{template}" version="azure-pipelines-2020.1"::: -->

```yaml
variables:
- template: string # Required as first property. Template file with variables.. 
  parameters:  # Parameters to map into a the template.
    string: string # Name/value pairs.
```


Properties that use this definition: [variables.](variables.md)

## Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `template`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Required as first parameter. Template file with variables. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `parameters`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string name/value pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Parameters to map into a the template. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines-2022"

<!-- :::api-definition signature="variable{template}" version="azure-pipelines-2022"::: -->

```yaml
variables:
- template: string # Required as first property. Template file with variables.. 
  parameters:  # Parameters to map into a the template.
    string: string # Name/value pairs.
```


Properties that use this definition: [variables.](variables.md)

## Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `template`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Required as first parameter. Template file with variables. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `parameters`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string name/value pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Parameters to map into a the template. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines"

<!-- :::api-definition signature="variable{template}" version="azure-pipelines"::: -->

```yaml
variables:
- template: string # Required as first property. Template file with variables.. 
  parameters:  # Parameters to map into a the template.
    string: string # Name/value pairs.
```


Properties that use this definition: [variables.](variables.md)

## Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `template`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Required as first parameter. Template file with variables. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `parameters`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string name/value pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Parameters to map into a the template. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end


<!-- Remarks -->


## Examples

In this example, a set of variables is repeated across multiple pipelines.
The variables are specified only once.

```yaml
# File: variables/build.yml
variables:
- name: vmImage
  value: vs2017-win2016
- name: arch
  value: x64
- name: config
  value: debug
```

```yaml
# File: component-x-pipeline.yml
variables:
- template: variables/build.yml  # Template reference
pool:
  vmImage: ${{ variables.vmImage }}
steps:
- script: build x ${{ variables.arch }} ${{ variables.config }}
```

```yaml
# File: component-y-pipeline.yml
variables:
- template: variables/build.yml  # Template reference
pool:
  vmImage: ${{ variables.vmImage }}
steps:
- script: build y ${{ variables.arch }} ${{ variables.config }}
```


## See also

- [Template types & usage - variable reuse](/azure/devops/pipelines/process/templates#variable-reuse)
- [Add & use variable groups](/azure/devops/pipelines/library/variable-groups)
- [Define variables](/azure/devops/pipelines/process/variables)
