### GCloud-Termux
> access and use Google Cloud Shell from Termux on Android » leveraging Docker and additional tools that are not available in Termux

<ol>
  <li>Install <a href="https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_universal.apk">Termux</a></li>
  <li>From Termux command line run:</li>
</ol>
<pre><code>curl -sS https://raw.githubusercontent.com/offici5l/GCloud-Termux/main/install | bash</code></pre>
  <li>login:</li>
</ol>
<pre><code>gcloud auth login</code></pre>
  <li>cloud-shell:</li>
</ol>
<pre><code>gcloud cloud-shell ssh</code></pre>