# transmission-kubernetes
Configuration for setting up transmission over VPN on Kubernetes

<pre><code>helm repo add bananaspliff https://bananaspliff.github.io/geek-charts
</code></pre>

<pre><code>helm repo update
</code></pre>

<pre><code>helm install transmission bananaspliff/transmission-openvpn --values.yaml
</code></pre>
