---
title: "Counter"
url: /refguide/metrics-counter/
weight: 10
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

{{% alert color="info" %}}
This activity can only be used in microflows.
{{% /alert %}}

## 1 Introduction

The **Counter** activity can be used to increment a metrics counter by a specific value.

## 2 Properties

An example of counter properties is represented in the image below:

{{< figure src="/attachments/refguide/modeling/application-logic/microflows-and-nanoflows/activities/metrics-activities/metrics-counter/counter-properties.png" alt="Counter Properties" class="no-border" >}}

There are two sets of properties for this activity, those in the dialog box on the left, and those in the properties pane on the right.

The **Counter** properties pane consists of the following sections:

* [Action](#action)
* [Common](#common)

## 3 Action Section {#action}

The **Action** section of the properties pane shows the action associated with this activity.

You can open a dialog box to configure this action by clicking the ellipsis (**…**) next to the action.

You can also open the dialog box by double-clicking the activity, or right-clicking the activity and selecting **Properties**.

### 3.1 Name

The name of the counter whose value you want to increment, which must adhere to the following rules:

* The name can only contain alpha-numeric characters, dots or underscores.
* The name must start with a letter.
* The name cannot start with `mx`, because this prefix is reserved for Mendix internal metrics.
* The name is case-insensitive.

{{% alert color="info" %}}
It is recommended to use a common prefix that uniquely defines your organisation and application.
{{% /alert %}}

### 3.2 Value

The value used to increment the counter's value. Values are specified with [expressions](/refguide/expressions/) and should be of type Integer/Long. It is only possible to increment the counter, so values cannot be negative.

### 3.3 Tags

You can specify a list of tags to enrich the counter name with key/value pairs. See [Tag Naming](https://micrometer.io/docs/concepts#_tag_naming) on the Micrometer site for more guidance on using tags.

## 4 Common Section {#common}

{{% snippet file="/static/_includes/refguide/microflow-common-section-link.md" %}}

## 5 Read More

* [Metric Configuration](/refguide/metrics/)
* [Metrics Activities](/refguide/metrics-activities/)
* [Meter Concepts](https://micrometer.io/docs/concepts)
