---
title: Get Started
---

Pulumi is an [open source](https://github.com/pulumi/pulumi) platform for
building and deploying cloud infrastructure and applications in your favorite
language on any cloud. Describe your resources in code -- VMs, networks,
databases, containers, serverless functions -- and the CLI safely and reliably
manages your cloud resources using an infrastructure-as-code approach. Create,
share, and reuse powerful cloud packages.

This tutorial will walk you through creating and deploying your first Pulumi program.

<!-- TODO make these big, nice looking, buttons. -->
<!-- TODO make it possible to select cloud and language from query params. -->

## Choose Your Cloud and Language

<label for="cloud">Cloud:</label>
<select id="cloud" onchange="selectHelper('cloud', clouds, this.value)">
    <option value="aws">AWS</option>
    <option value="azure">Azure</option>
    <option value="gcp">Google Cloud</option>
    <option value="kubernetes">Kubernetes</option>
</select>

<label for="language">Language:</label>
<select id="language" onchange="selectHelper('language', languages, this.value)">
    <option value="typescript">TypeScript</option>
    <option value="javascript">JavaScript</option>
    <option value="python">Python</option>
</select>

## Install Pulumi

<div class="install_macos" markdown="1">
To get started on macOS, install Pulumi through [Homebrew](https://brew.sh/):

```bash
$ brew install pulumi
```
</div>

<div class="install_linux" markdown="1">
To get started on Linux, run our installation script:

```bash
$ curl -fsSL https://get.pulumi.com | sh
```
</div>

<div class="install_windows" markdown="1">
To get started on Windows, run our installation script from a `cmd.exe` window:

```batch
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; iex ((New-Object System.Net.WebClient).DownloadString('https://get.pulumi.com/install.ps1'))" && SET "PATH=%PATH%;%USERPROFILE%\.pulumi\bin"
```
</div>

> See [installation details](install.md) for other platforms, manual
> installation steps, and troubleshooting.

<div class="cloud_aws" markdown="1">
## Configure AWS

TODO
</div>

<div class="cloud_azure" markdown="1">
## Configure Azure

TODO
</div>

<div class="cloud_gcp" markdown="1">
## Configure Google Cloud

TODO
</div>

<div class="cloud_kubernetes" markdown="1">
## Configure Kubernetes

TODO
</div>

<div class="language_typescript" markdown="1">
## TypeScript

TODO
</div>

<div class="language_javascript" markdown="1">
## JavaScript

TODO
</div>

<div class="language_python" markdown="1">
## Python

TODO
</div>

<script>
    function showHelper(id, value) {
        var e = document.getElementsByClassName(id + "_" + value)
        for (var i = 0; i < e.length; i++) {
            e[i].style.display = "block";
        }

        var s = document.getElementById(id);
        if (s) {
            for (var i = 0; i < s.options.length; i++) {
                if (s.options[i].value === value) {
                    s.selectedIndex = i;
                    break;
                }
            }
        }
    }

    function hideHelper(id, value) {
        var e = document.getElementsByClassName(id + "_" + value)
        for (var i = 0; i < e.length; i++) {
            e[i].style.display = "none";
        }
    }

    function selectHelper(id, values, value) {
        var found;
        for (var i = 0; i < values.length; i++) {
            if (value === values[i]) {
                showHelper(id, values[i]);
                found = true;
            } else {
                hideHelper(id, values[i]);
            }
        }
        if (!found) {
            showHelper(id, values[0]);
        }
    }

    var oses = ["linux", "macos", "windows"];
    if (navigator.appVersion.indexOf("Win") !== -1) {
        selectHelper("install", oses, "windows");
    } else if (navigator.appVersion.indexOf("Mac") !== -1) {
        selectHelper("install", oses, "macos");
    } else {
        // Otherwise, just show the command for Linux.
        selectHelper("install", oses, "linux");
    }

    var clouds = ["aws", "azure", "gcp", "kubernetes"];
    selectHelper("cloud", clouds, "aws");

    var languages = ["typescript", "javascript", "python"];
    selectHelper("language", languages, "typescript");
</script>
