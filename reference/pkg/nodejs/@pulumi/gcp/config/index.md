---
title: Module config
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../index.html">@pulumi/gcp</a> &gt; config

<div class="toggleVisible" markdown="1">
<div class="collapsed" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents" markdown="1">
* <a href="#accessToken">let accessToken</a>
* <a href="#credentials">let credentials</a>
* <a href="#project">let project</a>
* <a href="#region">let region</a>
* <a href="#scopes">let scopes</a>
* <a href="#zone">let zone</a>

<a href="https://github.com/pulumi/pulumi-gcp/blob/dfd50d3cd37076dc64bfff16a687877050b08fcb/sdk/nodejs/config/vars.ts">config/vars.ts</a> 
</div>
</div>
</div>


<h2 class="pdoc-module-header" id="accessToken">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/dfd50d3cd37076dc64bfff16a687877050b08fcb/sdk/nodejs/config/vars.ts#L9">let <b>accessToken</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> accessToken: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;accessToken&#34;)</span>;</pre>
</div>
<h2 class="pdoc-module-header" id="credentials">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/dfd50d3cd37076dc64bfff16a687877050b08fcb/sdk/nodejs/config/vars.ts#L10">let <b>credentials</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> credentials: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;credentials&#34;) || utilities.getEnv(&#34;GOOGLE_CREDENTIALS&#34;, &#34;GOOGLE_CLOUD_KEYFILE_JSON&#34;, &#34;GCLOUD_KEYFILE_JSON&#34;)</span>;</pre>
</div>
<h2 class="pdoc-module-header" id="project">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/dfd50d3cd37076dc64bfff16a687877050b08fcb/sdk/nodejs/config/vars.ts#L11">let <b>project</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> project: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;project&#34;) || utilities.getEnv(&#34;GOOGLE_PROJECT&#34;, &#34;GOOGLE_CLOUD_PROJECT&#34;, &#34;GCLOUD_PROJECT&#34;, &#34;CLOUDSDK_CORE_PROJECT&#34;)</span>;</pre>
</div>
<h2 class="pdoc-module-header" id="region">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/dfd50d3cd37076dc64bfff16a687877050b08fcb/sdk/nodejs/config/vars.ts#L12">let <b>region</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> region: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;region&#34;) || utilities.getEnv(&#34;GOOGLE_REGION&#34;, &#34;GCLOUD_REGION&#34;, &#34;CLOUDSDK_COMPUTE_REGION&#34;)</span>;</pre>
</div>
<h2 class="pdoc-module-header" id="scopes">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/dfd50d3cd37076dc64bfff16a687877050b08fcb/sdk/nodejs/config/vars.ts#L13">let <b>scopes</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> scopes: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>[] | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;string[]&gt;(&#34;scopes&#34;)</span>;</pre>
</div>
<h2 class="pdoc-module-header" id="zone">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/dfd50d3cd37076dc64bfff16a687877050b08fcb/sdk/nodejs/config/vars.ts#L14">let <b>zone</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> zone: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;zone&#34;) || utilities.getEnv(&#34;GOOGLE_ZONE&#34;, &#34;GCLOUD_ZONE&#34;, &#34;CLOUDSDK_COMPUTE_ZONE&#34;)</span>;</pre>
</div>
