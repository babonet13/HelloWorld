golang : Installation Guide (Package-based - Ubuntu/Debian)
==
Id Card
-
Keys criterias :
<table>
    <thead>
        <tr>
            <th>Criteria</th>
            <th>Value</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Linux Distro</td>
            <td>Ubuntu/Debian</td>
        </tr>
        <tr>
            <td>Install Mode</td>
            <td>Distro Specific Package</td>
        </tr>
        <tr>
            <td>Installed Binary</td>
            <td>/usr/local/go</td>
        </tr>
        <tr>
            <td>Configuration File</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Data Directory</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Default Port</td>
            <td>NA/</td>
        </tr>
    </tbody>
</table>

Reference(s)
-
<a href="https://golang.org/doc/install">The Go Programming Language / Getting Started</a>.  
<a href="https://github.com/golang/go/wiki/Ubuntu">Github / goland / go / Ubuntu</a>.  
<a href="https://tecadmin.net/install-go-on-ubuntu/">How to Install Go 1.10 on Ubuntu 18.04 LTS</a>.    

Prerequisite(s)
-
N/A

Installation
-
Install app
<pre><code>$ sudo apt-get update
$ sudo apt-get install -y golang-go</code></pre>

Configuration
-
Set "GOROOT" variable (define where Go package is installed on your system) : 
<pre><code>$ export GOROOT=/usr/local/go</code></pre>

Set "GOPATH" variable (define where Go projects are located) : 
<pre><code>$ export GOPATH=%HOME/go</code></pre>

Set "PATH" variable (location where the system look for binaries files) : 
<pre><code>$ export PATH=%GOPATH/bin:$GOROOT/bin</code></pre>

Test
-
Verify version :
<pre><code>$ go version</code></pre>

Verify environment variables :
<pre><code>$ go env</code></pre>