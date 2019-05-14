---
title: Module meta/v1
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../../index.html">@pulumi/kubernetes</a> &gt; <a href="../index.html">meta</a> &gt; v1

<div class="toggleVisible" markdown="1">
<div class="collapsed" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents" markdown="1">
* <a href="#Status">class Status</a>

<a href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts">meta/v1/Status.ts</a> 
</div>
</div>
</div>


<h2 class="pdoc-module-header" id="Status">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L11">class <b>Status</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>extends</span> <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

Status is a return value for calls that don't return other objects.

<h3 class="pdoc-member-header" id="Status-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L81"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> Status(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args?: inputApi.meta.v1.Status, opts?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a meta.v1.Status resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

</div>
<h3 class="pdoc-member-header" id="Status-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L76">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, opts?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Status'>Status</a></pre>


Get the state of an existing `Status` resource, as identified by `id`.
Typically this ID  is of the form <namespace>/<name>; if <namespace> is omitted, then (per
Kubernetes convention) the ID becomes default/<name>.

Pulumi will keep track of this resource using `name` as the Pulumi ID.

</div>
<h3 class="pdoc-member-header" id="Status-getInputs">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L80">method <b>getInputs</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>public </span>getInputs(): inputApi.meta.v1.Status</pre>

</div>
<h3 class="pdoc-member-header" id="Status-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L14">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

</div>
<h3 class="pdoc-member-header" id="Status-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L101">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

</div>
<h3 class="pdoc-member-header" id="Status-apiVersion">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L18">property <b>apiVersion</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>apiVersion: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='s2'>"v1"</span>&gt;;</pre>

APIVersion defines the versioned schema of this representation of an object. Servers should
convert recognized schemas to the latest internal value, and may reject unrecognized
values. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#resources

</div>
<h3 class="pdoc-member-header" id="Status-code">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L23">property <b>code</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>code: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number'>number</a></span>&gt;;</pre>

Suggested HTTP return code for this status, 0 if not set.

</div>
<h3 class="pdoc-member-header" id="Status-details">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L30">property <b>details</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>details: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;outputApi.meta.v1.StatusDetails&gt;;</pre>

Extended data associated with the reason.  Each reason may define its own extended details.
This field is optional and the data returned is not guaranteed to conform to any schema
except that defined by the reason type.

</div>
<h3 class="pdoc-member-header" id="Status-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L96">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>id: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>Output</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#ID'>ID</a>&gt;;</pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

</div>
<h3 class="pdoc-member-header" id="Status-kind">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L38">property <b>kind</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>kind: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='s2'>"Status"</span>&gt;;</pre>

Kind is a string value representing the REST resource this object represents. Servers may
infer this from the endpoint the client submits requests to. Cannot be updated. In
CamelCase. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#types-kinds

</div>
<h3 class="pdoc-member-header" id="Status-message">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L43">property <b>message</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>message: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

A human-readable description of the status of this operation.

</div>
<h3 class="pdoc-member-header" id="Status-metadata">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L49">property <b>metadata</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>metadata: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;outputApi.meta.v1.ListMeta&gt;;</pre>

Standard list metadata. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#types-kinds

</div>
<h3 class="pdoc-member-header" id="Status-reason">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L56">property <b>reason</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>reason: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

A machine-readable description of why this operation is in the "Failure" status. If this
value is empty there is no information available. A Reason clarifies an HTTP status code
but does not override it.

</div>
<h3 class="pdoc-member-header" id="Status-status">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/meta/v1/Status.ts#L62">property <b>status</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>status: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

Status of the operation. One of: "Success" or "Failure". More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#spec-and-status

</div>
<h3 class="pdoc-member-header" id="Status-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/f56730d2e7af6121d8e7db6c2c2b188bd2b78602/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L12">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>urn: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>Output</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#URN'>URN</a>&gt;;</pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

</div>
</div>