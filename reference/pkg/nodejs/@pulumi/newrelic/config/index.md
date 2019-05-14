---
title: Module config
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../index.html">@pulumi/newrelic</a> &gt; config

<div class="toggleVisible" markdown="1">
<div class="collapsed" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents" markdown="1">
* <a href="#apiKey">let apiKey</a>
* <a href="#apiUrl">let apiUrl</a>
* <a href="#infraApiUrl">let infraApiUrl</a>

<a href="/config/vars.ts">config/vars.ts</a> 
</div>
</div>
</div>


<h2 class="pdoc-module-header" id="apiKey">
<a class="pdoc-member-name" href="/config/vars.ts#L9">let <b>apiKey</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> apiKey: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> = <span class='s2'> utilities.requireWithDefault(() =&gt; __config.require(&#34;apiKey&#34;), utilities.getEnv(&#34;NEWRELIC_API_KEY&#34;))</span>;</pre>
</div>
<h2 class="pdoc-module-header" id="apiUrl">
<a class="pdoc-member-name" href="/config/vars.ts#L10">let <b>apiUrl</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> apiUrl: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;apiUrl&#34;) || (utilities.getEnv(&#34;NEWRELIC_API_URL&#34;) || &#34;https://api.newrelic.com/v2&#34;)</span>;</pre>
</div>
<h2 class="pdoc-module-header" id="infraApiUrl">
<a class="pdoc-member-name" href="/config/vars.ts#L11">let <b>infraApiUrl</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> infraApiUrl: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;infraApiUrl&#34;) || (utilities.getEnv(&#34;NEWRELIC_INFRA_API_URL&#34;) || &#34;https://infra-api.newrelic.com/v2&#34;)</span>;</pre>
</div>