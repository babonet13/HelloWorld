Java
==

How to install several Java version ?
-

1. Installer Homebrew (Package Manager)   
https://brew.sh/index_fr
<pre><code>$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"</code></pre>

2. Installer Cask (Package Manager Companion)   
https://github.com/Homebrew/homebrew-cask
<pre><code>$ brew tap caskroom/cask</code></pre>
ou
<pre><code>$ brew tap homebrew/cask-versions</code></pre

3. Installer jenv   
https://www.jenv.be/
<pre><code>$ brew install jenv</code></pre>

4. Gérer les versions de Java   
https://www.it-swarm.dev/fr/java/mac-os-x-et-plusieurs-versions-de-java/1049449791/
<pre><code>$ brew search Java</code></pre>
<pre><code>$ brew tap caskroom/versions</code></pre>
<pre><code>$ brew cask install java6</code></pre>
