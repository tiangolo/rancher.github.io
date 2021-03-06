---
title: API
layout: rancher-default
version: latest
lang: zh
---

## pullTask



### Resource Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
description | string | Optional | Yes | - | 
id | int | - | - | - | The unique identifier for the pullTask
image | string | Yes | - | - | 
labels | map[string] | Optional | - | - | 
mode | enum | Yes | - | all | 
name | string | Optional | Yes | - | 
status | map[string] | - | - | - | 


Please read more about the [common resource fields]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/common/). 
These fields are read only and applicable to almost every resource. We have segregated them from the list above.


### Operations
{::options parse_block_html="true" /}



<div class="action">
<span class="header">
Create
<span class="headerright">POST:  <code>/v1/pullTask</code></span></span>
<div class="action-contents">
{% highlight json %} 
{

	"description": "string",

	"image": "string",

	"labels": {

		"key1": "value1",

		"key2": "value2",

		"keyN": "valueN"

	},

	"mode": "all",

	"name": "string"

} 
{% endhighlight %}
</div>
</div>











### Actions

<div class="action">
<span class="header">
activate
<span class="headerright">POST:  <code>${actions.activate}</code></span></span>
<div class="action-contents">
To activate the pullTask
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/genericObject/">genericObject</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
deactivate
<span class="headerright">POST:  <code>${actions.deactivate}</code></span></span>
<div class="action-contents">
To deactivate the pullTask
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/genericObject/">genericObject</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
purge
<span class="headerright">POST:  <code>${actions.purge}</code></span></span>
<div class="action-contents">
To purge the pullTask
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/genericObject/">genericObject</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
remove
<span class="headerright">POST:  <code>${actions.remove}</code></span></span>
<div class="action-contents">
To remove the pullTask
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/genericObject/">genericObject</a> resource</span>
</div>
</div>

<div class="action">
<span class="header">
restore
<span class="headerright">POST:  <code>${actions.restore}</code></span></span>
<div class="action-contents">
To restore the pullTask
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/genericObject/">genericObject</a> resource</span>
</div>
</div>

