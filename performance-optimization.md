---


---

<h1 id="oauth-2.0-server"><a href="https://oauth2.thephpleague.com/">OAuth 2.0 Server</a></h1>
<h2 id="reference-for-oauth-server-">Reference For OAuth Server :</h2>
<pre><code>	  1- https://oauth2.thephpleague.com
	  2- https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2
	  3- https://tools.ietf.org/html/rfc6749
</code></pre>
<h2 id="oauth-roles-">OAuth Roles :</h2>
<pre><code>       1- Resource Owner 
       2- Client
       3- Resource Server 
       4- Authorization Server
</code></pre>
<h2 id="types-of-grant-">Types Of Grant :</h2>
<pre><code>      1- Client Credentials Grant
      2- Password Grant
      3- Authorization code grant
      4- Implicit Grant
      5- Resource Owner Password Credentials Grant
</code></pre>
<h2 id="how-can-we-decide-which-type-of-grant-to-use-">How Can We Decide Which Type Of Grant To Use :</h2>
<pre><code>     This Based On What is The Type Of Client First Party Or Third Party. If The Client is Third Party We Must Use Authorization code grant But If The client Is Trusted Or First Party We Can Depend On Password Grant ..... Finally We Can use Client Credentials Grant in Machine To Machine Credentials Like Cron Job
</code></pre>

