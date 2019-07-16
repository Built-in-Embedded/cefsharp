

```.NET
dotnet add package CefSharp.WinForms --version 75.0.110-CI3193 --source https://www.myget.org/F/cefsharp/api/v3/index.json
```


 <div class="tabs-top">
            <ul class="nav nav-tabs">
                <li class=""><a href="#nuget" data-toggle="tab">NuGet (PM Console)</a></li>
                <li class=""><a href="#nugetexe" data-toggle="tab">NuGet.exe</a></li>
                <li class="active"><a href="#dotnetexe" data-toggle="tab">.NET CLI</a></li>
                <li class=""><a href="#csproj" data-toggle="tab">.csproj</a></li>
                <li><a href="#paket" data-toggle="tab">Paket</a></li>
                <li><a href="#chocolatey" data-toggle="tab">Chocolatey</a></li>
                <li><a href="#psget" data-toggle="tab">PowerShellGet</a></li>
            </ul>

 <div class="tab-content snippets">


 <div class="tab-pane" id="nuget">
                    <div class="terminal-commandWrapper">
                        <div class="terminal-commandPrompt">
                            <p class="terminal-command">
                                PM&gt; Install-Package CefSharp.WinForms -Version 75.0.110-CI3193 -Source https://www.myget.org/F/cefsharp/api/v3/index.json
                            </p>
                        </div>
                    </div>
                        <span class="clippy-container" style="float: none;">
        <span class="clippy-button" title="Copy to clipboard" data-bind="clipboard: ko.observable('Install-Package CefSharp.WinForms -Version 75.0.110-CI3193 -Source https://www.myget.org/F/cefsharp/api/v3/index.json')"></span>
    </span>
    <a href="#" title="Copy to clipboard" data-bind="clipboard: ko.observable('Install-Package CefSharp.WinForms -Version 75.0.110-CI3193 -Source https://www.myget.org/F/cefsharp/api/v3/index.json')">Copy to clipboard</a>

 </div>
                <div class="tab-pane" id="nugetexe">
                    <div class="terminal-commandWrapper">
                        <div class="terminal-commandPrompt">
                            <p class="terminal-command">
                                &gt; nuget.exe install CefSharp.WinForms -Version 75.0.110-CI3193 -Source https://www.myget.org/F/cefsharp/api/v3/index.json
                            </p>
                        </div>
                    </div>
                        <span class="clippy-container" style="float: none;">
        <span class="clippy-button" title="Copy to clipboard" data-bind="clipboard: ko.observable('nuget.exe install CefSharp.WinForms -Version 75.0.110-CI3193 -Source https://www.myget.org/F/cefsharp/api/v3/index.json')"></span>
    </span>
    <a href="#" title="Copy to clipboard" data-bind="clipboard: ko.observable('nuget.exe install CefSharp.WinForms -Version 75.0.110-CI3193 -Source https://www.myget.org/F/cefsharp/api/v3/index.json')">Copy to clipboard</a>

 </div>
                <div class="tab-pane active" id="dotnetexe">
                    <div class="terminal-commandWrapper">
                        <div class="terminal-commandPrompt">
                            <p class="terminal-command">
                                &gt; dotnet add package CefSharp.WinForms --version 75.0.110-CI3193 --source https://www.myget.org/F/cefsharp/api/v3/index.json
                            </p>
                        </div>
                    </div>
                        <span class="clippy-container" style="float: none;">
        <span class="clippy-button" title="Copy to clipboard" data-bind="clipboard: ko.observable('dotnet add package CefSharp.WinForms --version 75.0.110-CI3193 --source https://www.myget.org/F/cefsharp/api/v3/index.json')"></span>
    </span>
    <a href="#" title="Copy to clipboard" data-bind="clipboard: ko.observable('dotnet add package CefSharp.WinForms --version 75.0.110-CI3193 --source https://www.myget.org/F/cefsharp/api/v3/index.json')">Copy to clipboard</a>


      </div>
                <div class="tab-pane" id="csproj">
                    <pre class="editor ace_editor ace-tomorrow" style="height: 14px;"><textarea class="ace_text-input" wrap="off" autocorrect="off" autocapitalize="off" spellcheck="false" readonly="" style="opacity: 0; font-size: 1px; height: 1px; width: 1px; top: 13px; left: 4px;"></textarea><div class="ace_gutter" aria-hidden="true" style="display: none; left: 0px;"><div class="ace_layer ace_gutter-layer ace_folding-enabled" style="height: 1e+06px;"></div></div><div class="ace_scroller" style="left: 0px; right: 0px; bottom: 0px;"><div class="ace_content" style="top: 0px; left: 0px; width: 754px; height: 42px;"><div class="ace_layer ace_print-margin-layer"><div class="ace_print-margin" style="left: 4px; visibility: visible;"></div></div><div class="ace_layer ace_marker-layer"><div class="ace_active-line" style="height: 14px; top: 0px; left: 0px; right: 0px;"></div></div><div class="ace_layer ace_text-layer" style="height: 1e+06px; margin: 0px 4px; top: 0px; left: 0px;"><div class="ace_line" style="height: 14px; top: 0px;"><span class="ace_meta ace_tag ace_punctuation ace_tag-open ace_xml">&lt;</span><span class="ace_meta ace_tag ace_tag-name ace_xml">PackageReference</span><span class="ace_text ace_tag-whitespace ace_xml"> </span><span class="ace_entity ace_other ace_attribute-name ace_xml">Include</span><span class="ace_keyword ace_operator ace_attribute-equals ace_xml">=</span><span class="ace_string ace_attribute-value ace_xml">"CefSharp.WinForms"</span><span class="ace_text ace_tag-whitespace ace_xml"> </span><span class="ace_entity ace_other ace_attribute-name ace_xml">Version</span><span class="ace_keyword ace_operator ace_attribute-equals ace_xml">=</span><span class="ace_string ace_attribute-value ace_xml">"75.0.110-CI3193"</span><span class="ace_text ace_tag-whitespace ace_xml"> </span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">/&gt;</span></div></div><div class="ace_layer ace_marker-layer"></div><div class="ace_layer ace_cursor-layer ace_hidden-cursors"><div class="ace_cursor" style="display: block; top: 0px; left: 4px; width: 7px; height: 14px;"></div></div></div></div><div class="ace_scrollbar ace_scrollbar-v" style="display: none; width: 22px; bottom: 0px;"><div class="ace_scrollbar-inner" style="width: 22px; height: 14px;">&nbsp;</div></div><div class="ace_scrollbar ace_scrollbar-h" style="display: none; height: 22px; left: 0px; right: 0px;"><div class="ace_scrollbar-inner" style="height: 22px; width: 754px;">&nbsp;</div></div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: hidden;"><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: visible;">הההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההה</div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font-style: inherit; font-variant: inherit; font-stretch: inherit; font-size: inherit; line-height: inherit; font-family: inherit; overflow: visible;">XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</div></div></pre>
                        <span class="clippy-container" style="float: none;">
        <span class="clippy-button" title="Copy to clipboard" data-bind="clipboard: ko.observable('<PackageReference Include=&quot;CefSharp.WinForms&quot; Version=&quot;75.0.110-CI3193&quot; />')"></span>
    </span>
    <a href="#" title="Copy to clipboard" data-bind="clipboard: ko.observable('<PackageReference Include=&quot;CefSharp.WinForms&quot; Version=&quot;75.0.110-CI3193&quot; />')">Copy to clipboard</a>

                </div>
                <div class="tab-pane" id="paket">
                    <pre class="editor ace_editor ace-tomorrow"><textarea class="ace_text-input" wrap="off" autocorrect="off" autocapitalize="off" spellcheck="false" readonly="" style="opacity: 0; font-size: 1px;"></textarea><div class="ace_gutter" aria-hidden="true" style="display: none;"><div class="ace_layer ace_gutter-layer ace_folding-enabled" style="height: 1e+06px;"></div></div><div class="ace_scroller"><div class="ace_content"><div class="ace_layer ace_print-margin-layer"><div class="ace_print-margin" style="left: 4px; visibility: visible;"></div></div><div class="ace_layer ace_marker-layer"></div><div class="ace_layer ace_text-layer" style="height: 1e+06px; margin: 0px 4px;"></div><div class="ace_layer ace_marker-layer"></div><div class="ace_layer ace_cursor-layer ace_hidden-cursors"><div class="ace_cursor"></div></div></div></div><div class="ace_scrollbar ace_scrollbar-v" style="display: none; width: 22px;"><div class="ace_scrollbar-inner" style="width: 22px;">&nbsp;</div></div><div class="ace_scrollbar ace_scrollbar-h" style="display: none; height: 22px;"><div class="ace_scrollbar-inner" style="height: 22px;">&nbsp;</div></div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: hidden;"><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: visible;"></div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: visible;">XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</div></div></pre>
                        <span class="clippy-container" style="float: none;">
        <span class="clippy-button" title="Copy to clipboard" data-bind="clipboard: ko.observable('source https://www.myget.org/F/cefsharp/api/v3/index.json\r\n\r\nnuget CefSharp.WinForms  ~> 75.0.110-CI3193')"></span>
    </span>
    <a href="#" title="Copy to clipboard" data-bind="clipboard: ko.observable('source https://www.myget.org/F/cefsharp/api/v3/index.json\r\n\r\nnuget CefSharp.WinForms  ~> 75.0.110-CI3193')">Copy to clipboard</a>

                </div>
                <div class="tab-pane" id="chocolatey">
                    <div class="terminal-commandWrapper">
                        <div class="terminal-commandPrompt">
                            <p class="terminal-command">
                                &gt; choco install CefSharp.WinForms --version 75.0.110-CI3193 --source https://www.myget.org/F/cefsharp/api/v2
                            </p>
                        </div>
                    </div>
                        <span class="clippy-container" style="float: none;">
        <span class="clippy-button" title="Copy to clipboard" data-bind="clipboard: ko.observable('choco install CefSharp.WinForms --version 75.0.110-CI3193 --source https://www.myget.org/F/cefsharp/api/v2')"></span>
    </span>
    <a href="#" title="Copy to clipboard" data-bind="clipboard: ko.observable('choco install CefSharp.WinForms --version 75.0.110-CI3193 --source https://www.myget.org/F/cefsharp/api/v2')">Copy to clipboard</a>

                </div>
                <div class="tab-pane" id="psget">
                    <pre class="editor ace_editor ace-tomorrow"><textarea class="ace_text-input" wrap="off" autocorrect="off" autocapitalize="off" spellcheck="false" readonly="" style="opacity: 0; font-size: 1px;"></textarea><div class="ace_gutter" aria-hidden="true" style="display: none;"><div class="ace_layer ace_gutter-layer ace_folding-enabled" style="height: 1e+06px;"></div></div><div class="ace_scroller"><div class="ace_content"><div class="ace_layer ace_print-margin-layer"><div class="ace_print-margin" style="left: 4px; visibility: visible;"></div></div><div class="ace_layer ace_marker-layer"></div><div class="ace_layer ace_text-layer" style="height: 1e+06px; margin: 0px 4px;"></div><div class="ace_layer ace_marker-layer"></div><div class="ace_layer ace_cursor-layer ace_hidden-cursors"><div class="ace_cursor"></div></div></div></div><div class="ace_scrollbar ace_scrollbar-v" style="display: none; width: 22px;"><div class="ace_scrollbar-inner" style="width: 22px;">&nbsp;</div></div><div class="ace_scrollbar ace_scrollbar-h" style="display: none; height: 22px;"><div class="ace_scrollbar-inner" style="height: 22px;">&nbsp;</div></div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: hidden;"><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: visible;"></div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: visible;">XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</div></div></pre>
                        <span class="clippy-container" style="float: none;">
        <span class="clippy-button" title="Copy to clipboard" data-bind="clipboard: ko.observable('Import-Module PowerShellGet\r\nRegister-PSRepository -Name &quot;cefsharp&quot; -SourceLocation &quot;https://www.myget.org/F/cefsharp/api/v2&quot;\r\nInstall-Module -Name &quot;CefSharp.WinForms&quot; -RequiredVersion &quot;75.0.110-CI3193&quot; -Repository &quot;cefsharp&quot; -AllowPreRelease')"></span>
    </span>
    <a href="#" title="Copy to clipboard" data-bind="clipboard: ko.observable('Import-Module PowerShellGet\r\nRegister-PSRepository -Name &quot;cefsharp&quot; -SourceLocation &quot;https://www.myget.org/F/cefsharp/api/v2&quot;\r\nInstall-Module -Name &quot;CefSharp.WinForms&quot; -RequiredVersion &quot;75.0.110-CI3193&quot; -Repository &quot;cefsharp&quot; -AllowPreRelease')">Copy to clipboard</a>

                </div>
            </div>
        </div>

            <hr>
            <p>
                Browse the sources in this package using Visual Studio or WinDbg by configuring the following symbol server URL: <code>https://www.myget.org/F/cefsharp/symbols/</code>
            </p>

        <hr>

        <div class="tabs-top">
        <ul class="nav nav-tabs">
                <li class="active"><a href="#readme" data-toggle="tab">Readme</a></li>

                <li class=""><a href="#releasenotes" data-toggle="tab">Release notes</a></li>

                <li class=""><a href="#dependencies" data-toggle="tab">Dependencies</a></li>



                <li class=""><a href="#sources" class="loadSources" data-toggle="tab">Source code</a></li>
                <li class=""><a href="#symbols" data-toggle="tab">Symbols</a></li>
            
        </ul>

            <div class="tab-content">
                    <div class="tab-pane active" id="readme">
                        <p><a href="https://cefsharp.github.io/" title="CefSharp - Embedded Chromium for .NET"><img src="logo.png" alt="CefSharp Logo"></a></p>
<p><a href="https://ci.appveyor.com/project/cefsharp/cefsharp/branch/master"><img src="https://ci.appveyor.com/api/projects/status/9g4mcuqruc283g66/branch/master?svg=true" alt="Build status"></a>
<a href="https://www.nuget.org/packages/CefSharp.WinForms/"><img src="https://img.shields.io/nuget/v/CefSharp.WinForms.svg?style=flat&amp;label=WinForms" alt="CefSharp.WinForms"></a>
<a href="https://www.nuget.org/packages/CefSharp.Wpf/"><img src="https://img.shields.io/nuget/v/CefSharp.Wpf.svg?style=flat&amp;label=Wpf" alt="CefSharp.Wpf"></a>
<a href="https://www.nuget.org/packages/CefSharp.OffScreen/"><img src="https://img.shields.io/nuget/v/CefSharp.OffScreen.svg?style=flat&amp;label=OffScreen" alt="CefSharp.OffScreen"></a></p>
<p>Got a quick question? Jump on <a href="https://gitter.im/cefsharp/CefSharp?utm_source=badge&amp;utm_medium=badge&amp;utm_campaign=pr-badge"><img src="https://badges.gitter.im/Join%20Chat.svg" alt="Gitter"></a></p>
<p><a href="https://cefsharp.github.io/">CefSharp</a> lets you embed Chromium in .NET apps. It is a lightweight .NET wrapper around the <a href="https://bitbucket.org/chromiumembedded/cef">Chromium Embedded Framework (CEF)</a> by Marshall A. Greenblatt. About 30% of the bindings are written in C++/CLI with the majority of code here is C#. It can be used from C# or VB, or any other CLR language. CefSharp provides both WPF and WinForms web browser control implementations.</p>
<p>CefSharp is <a href="https://opensource.org/licenses/BSD-3-Clause" title="BSD License">BSD</a> licensed, so it can be used in both proprietary and free/open source applications. For the full details, see the <a href="LICENSE">LICENSE</a> file.</p>
<p>If you like and use CefSharp please consider signing up for a small monthly donation, even $25 can help tremendously. See <a href="#Financial-Support">Financial Support</a> for more details.</p>
<h2 id="releases">Releases</h2>
<p>Stable binaries are released on NuGet, and contain everything you need  to embed Chromium in your .Net/CLR application. For usage see the <a href="https://github.com/cefsharp/CefSharp/wiki/Quick-Start">Quick Start</a> guide or <a href="https://github.com/cefsharp/CefSharp/wiki/Frequently-asked-questions#CefSharp_binaries">FAQ #8</a>.</p>
<ul>
<li><a href="https://www.nuget.org/packages/CefSharp.WinForms/">CefSharp.WinForms</a></li>
<li><a href="https://www.nuget.org/packages/CefSharp.Wpf/">CefSharp.Wpf</a></li>









Browse the sources in this package using Visual Studio or WinDbg by configuring 
the following symbol server URL: 
```yml
https://www.myget.org/F/cefsharp/symbols/ 
```


***

[![CefSharp Logo](logo.png)](https://cefsharp.github.io/ "CefSharp - Embedded Chromium for .NET")

[![Build status](https://ci.appveyor.com/api/projects/status/9g4mcuqruc283g66/branch/master?svg=true)](https://ci.appveyor.com/project/cefsharp/cefsharp/branch/master)
[![CefSharp.WinForms](https://img.shields.io/nuget/v/CefSharp.WinForms.svg?style=flat&label=WinForms)](https://www.nuget.org/packages/CefSharp.WinForms/)
[![CefSharp.Wpf](https://img.shields.io/nuget/v/CefSharp.Wpf.svg?style=flat&label=Wpf)](https://www.nuget.org/packages/CefSharp.Wpf/)
[![CefSharp.OffScreen](https://img.shields.io/nuget/v/CefSharp.OffScreen.svg?style=flat&label=OffScreen)](https://www.nuget.org/packages/CefSharp.OffScreen/)

Got a quick question? Jump on [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/cefsharp/CefSharp?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

[CefSharp](https://cefsharp.github.io/) lets you embed Chromium in .NET apps. It is a lightweight .NET wrapper around the [Chromium Embedded Framework (CEF)](https://bitbucket.org/chromiumembedded/cef) by Marshall A. Greenblatt. About 30% of the bindings are written in C++/CLI with the majority of code here is C#. It can be used from C# or VB, or any other CLR language. CefSharp provides both WPF and WinForms web browser control implementations.

CefSharp is [BSD](https://opensource.org/licenses/BSD-3-Clause "BSD License") licensed, so it can be used in both proprietary and free/open source applications. For the full details, see the [LICENSE](LICENSE) file. 

If you like and use CefSharp please consider signing up for a small monthly donation, even $25 can help tremendously. See [Financial Support](#Financial-Support) for more details.

## Releases

Stable binaries are released on NuGet, and contain everything you need  to embed Chromium in your .Net/CLR application. For usage see the [Quick Start](https://github.com/cefsharp/CefSharp/wiki/Quick-Start) guide or [FAQ #8](https://github.com/cefsharp/CefSharp/wiki/Frequently-asked-questions#CefSharp_binaries).

- [CefSharp.WinForms](https://www.nuget.org/packages/CefSharp.WinForms/)
- [CefSharp.Wpf](https://www.nuget.org/packages/CefSharp.Wpf/)
- [CefSharp.OffScreen](https://www.nuget.org/packages/CefSharp.OffScreen/)

## Documentation

* See the [CefSharp.Wpf.Example](https://github.com/cefsharp/CefSharp/tree/master/CefSharp.Wpf.Example) or [CefSharp.WinForms.Example](https://github.com/cefsharp/CefSharp/tree/master/CefSharp.WinForms.Example) projects for example web browsers built with CefSharp. They demo most of the available features.
* See the [CefSharp.MinimalExample](https://github.com/cefsharp/CefSharp.MinimalExample/) project for a basic demo of using the CefSharp NuGet packages.
* See the [General Usage Guide](https://github.com/cefsharp/CefSharp/wiki/General-Usage) in help getting started/dealing with common scenarios.
* See the [Wiki](https://github.com/cefsharp/CefSharp/wiki) for work-in-progress documentation
* See the [FAQ](https://github.com/cefsharp/CefSharp/wiki/Frequently-asked-questions) for help with common issues
* Upgrading from an earlier version of CefSharp? See the [ChangeLog](https://github.com/cefsharp/CefSharp/wiki/ChangeLog) for breaking changes and upgrade tips.
* [CefSharp API](https://cefsharp.github.io/api/55.0.0/) generated from the source code comments.

## Contact

If you have a very simple question please start by asking it on [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/cefsharp/CefSharp?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge). Please keep the `Issue Tracker` for **Bugs** only please! Before submitting a `PR` please read [CONTRIBUTING](https://github.com/cefsharp/CefSharp/blob/master/CONTRIBUTING.md)

[Stackoverflow](https://stackoverflow.com/questions/tagged/cefsharp) is generally where questions should be asked, please search before posting, thanks!

## Branches & Forks

This is the `official` CefSharp fork, as maintained by the CefSharp community. You can also view [the entire network of public forks/branches](https://github.com/cefsharp/CefSharp/network).

Development is done in the `master` branch. New features are preferably added in feature branches, if the changes are more than trivial. New `PR's` should be targeted against `master`.

When a new release is imminent a `release` branch is created. We try to avoid making public facing `API` changes in `release` branches (Adding new features is fine, just not breaking changes).

### Releases

**CI Builds**<br/>
Every commit on `master` produces a `Nuget` package. Use at your own risk!


- [![MyGet Pre Release](https://img.shields.io/myget/cefsharp/v/CefSharp.WinForms.svg?style=flat&label=WinForms)](https://www.myget.org/feed/cefsharp/package/nuget/CefSharp.WinForms)
- [![MyGet Pre Release](https://img.shields.io/myget/cefsharp/v/CefSharp.Wpf.svg?style=flat&label=Wpf)](https://www.myget.org/feed/cefsharp/package/nuget/CefSharp.Wpf)
- [![MyGet Pre Release](https://img.shields.io/myget/cefsharp/v/CefSharp.OffScreen.svg?style=flat&label=OffScreen)](https://www.myget.org/feed/cefsharp/package/nuget/CefSharp.OffScreen)

**Pre-release**<br>

- [![CefSharp.WinForms](http://img.shields.io/nuget/vpre/CefSharp.WinForms.svg?style=flat&label=WinForms)](http://www.nuget.org/packages/CefSharp.WinForms/)
- [![CefSharp.Wpf](http://img.shields.io/nuget/vpre/CefSharp.Wpf.svg?style=flat&label=Wpf)](http://www.nuget.org/packages/CefSharp.Wpf/)
- [![CefSharp.OffScreen](http://img.shields.io/nuget/vpre/CefSharp.OffScreen.svg?style=flat&label=OffScreen)](http://www.nuget.org/packages/CefSharp.OffScreen/)

**Stable**<br>
- [![CefSharp.WinForms](http://img.shields.io/nuget/v/CefSharp.WinForms.svg?style=flat&label=WinForms)](http://www.nuget.org/packages/CefSharp.WinForms/)
- [![CefSharp.Wpf](http://img.shields.io/nuget/v/CefSharp.Wpf.svg?style=flat&label=Wpf)](http://www.nuget.org/packages/CefSharp.Wpf/)
- [![CefSharp.OffScreen](http://img.shields.io/nuget/v/CefSharp.OffScreen.svg?style=flat&label=OffScreen)](http://www.nuget.org/packages/CefSharp.OffScreen/)

### Release Branches

With each release a new branch is created, for example the `53.0.1` release corresponds to the `cefsharp/53` branch.
If you're new to `CefSharp` and are downloading the source to check it out, please use a **Release** branch

| Branch                                                               | CEF Version | VC++ Version | .Net Version | Status |
|----------------------------------------------------------------------|------|------|-------|-----------------|
| [master](https://github.com/cefsharp/CefSharp/)                      | 3729 | 2015 | 4.5.2 | Development     |
| [cefsharp/73](https://github.com/cefsharp/CefSharp/tree/cefsharp/73) | 3683 | 2015 | 4.5.2 | **Release**     |
| [cefsharp/71](https://github.com/cefsharp/CefSharp/tree/cefsharp/71) | 3578 | 2015 | 4.5.2 | Unsupported     |
| [cefsharp/69](https://github.com/cefsharp/CefSharp/tree/cefsharp/69) | 3497 | 2015 | 4.5.2 | Unsupported     |
| [cefsharp/67](https://github.com/cefsharp/CefSharp/tree/cefsharp/67) | 3396 | 2015 | 4.5.2 | Unsupported     |
| [cefsharp/65](https://github.com/cefsharp/CefSharp/tree/cefsharp/65) | 3325 | 2015 | 4.5.2 | Unsupported     |
| [cefsharp/63](https://github.com/cefsharp/CefSharp/tree/cefsharp/63) | 3239 | 2013 | 4.5.2 | Unsupported     |
| [cefsharp/62](https://github.com/cefsharp/CefSharp/tree/cefsharp/62) | 3202 | 2013 | 4.5.2 | Unsupported     |
| [cefsharp/57](https://github.com/cefsharp/CefSharp/tree/cefsharp/57) | 2987 | 2013 | 4.5.2 | Unsupported     |
| [cefsharp/55](https://github.com/cefsharp/CefSharp/tree/cefsharp/55) | 2883 | 2013 | 4.5.2 | Unsupported     |
| [cefsharp/53](https://github.com/cefsharp/CefSharp/tree/cefsharp/53) | 2785 | 2013 | 4.5.2 | Unsupported     |
| [cefsharp/51](https://github.com/cefsharp/CefSharp/tree/cefsharp/51) | 2704 | 2013 | 4.5.2 | Unsupported     |
| [cefsharp/49](https://github.com/cefsharp/CefSharp/tree/cefsharp/49) | 2623 | 2013 | 4.0   | Unsupported     |
| [cefsharp/47](https://github.com/cefsharp/CefSharp/tree/cefsharp/47) | 2526 | 2013 | 4.0   | Unsupported     |
| [cefsharp/45](https://github.com/cefsharp/CefSharp/tree/cefsharp/45) | 2454 | 2013 | 4.0   | Unsupported     |
| [cefsharp/43](https://github.com/cefsharp/CefSharp/tree/cefsharp/43) | 2357 | 2012 | 4.0   | Unsupported     |
| [cefsharp/41](https://github.com/cefsharp/CefSharp/tree/cefsharp/41) | 2272 | 2012 | 4.0   | Unsupported     |
| [cefsharp/39](https://github.com/cefsharp/CefSharp/tree/cefsharp/39) | 2171 | 2012 | 4.0   | Unsupported     |
| [cefsharp/37](https://github.com/cefsharp/CefSharp/tree/cefsharp/37) | 2062 | 2012 | 4.0   | Unsupported     |


## Financial Support

To continue developing/supporting the project I (@amaitland) am asking for financial contributions. Donations of any size are greatly appreciated!

`75.0.0` Release: [![Bountysource](https://api.bountysource.com/badge/issue?issue_id=76601097)](https://www.bountysource.com/issues/76601097-funding-request-release-75-0-0?utm_source=76601097&utm_medium=shield&utm_campaign=ISSUE_BADGE)

Recurring contributions can be made through [BountySource Salt](https://salt.bountysource.com/teams/cefsharp) or one time contributions through [PayPal](https://paypal.me/AlexMaitland)

Now that I (@amaitland) am a stay at home dad your contributions are the only reason I'm allowed to continue working on the project. Without continued funding the time I currently spend on the project will have to be put into finding other paid work.

## Links

- [CefGlue](https://bitbucket.org/xilium/xilium.cefglue/): An alternative .NET CEF wrapper built using P/Invoke.
- [ChromiumFx](https://bitbucket.org/chromiumfx/chromiumfx) : Another P/Invoke .Net CEF wrapper
- [CEF Bitbucket Project](https://bitbucket.org/chromiumembedded/cef/overview) : The official CEF issue tracker
- [CEF Forum](http://magpcss.org/ceforum/) : The official CEF Forum
- [CEF API Docs](http://magpcss.org/ceforum/apidocs3/index-all.html) : Well worth a read if you are implementing a new feature
- [CefSharp API Doc](http://cefsharp.github.io/api/)

## Projects using CefSharp

- [HtmlView](https://github.com/MISoftware/HtmlView) : Visual Studio extension bringing CefSharp for showing HTML pages inside VS.
- [Chromely](https://github.com/mattkol/Chromely) : Build .NET/.NET Core HTML5 desktop apps using cross-platform native GUI API.
- [SharpBrowser](https://github.com/sharpbrowser/SharpBrowser) : The fastest web browser for C# with tabbed browsing and HTML5/CSS3.
