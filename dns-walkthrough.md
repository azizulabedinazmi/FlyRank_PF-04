# DNS walkthrough

The Domain Name System (DNS) is the internet's directory. People use
readable names such as `azizulabedinazmi.netlify.app`, while computers
connect to servers using IP addresses. DNS translates the name into the
address needed to load the website.

When someone enters the site address in a browser, the browser first checks
its own cache. If it does not already know the answer, the device asks a DNS
resolver, usually provided by the internet service provider or a public DNS
service. The resolver looks for the answer, using its cache when possible.
Otherwise, it follows the DNS hierarchy: a root server points it to the
appropriate top-level-domain nameserver, and that nameserver points it to the
domain's authoritative nameserver. The authoritative nameserver stores the
actual DNS records and returns the result to the resolver. The resolver sends
that result back to the device, which can then connect to the hosting
provider. The browser uses HTTPS to request the page, and the host returns
the site's files.

A DNS record is an instruction about a domain. An `A` record maps a name
directly to an IPv4 address. A `CNAME` record maps one hostname to another
hostname instead. For example, a custom `www` hostname can use a CNAME that
points to a hosting provider's assigned hostname. The resolver follows that
alias and then looks up the final address. CNAMEs are useful when the host
manages changing server addresses, because the site owner does not have to
update an IP address manually.

For this assignment, Netlify provides the public `netlify.app` hostname and
automatically serves the site over HTTPS. A custom domain is optional. If I
connect one later, I would add the DNS records requested by Netlify at my
domain registrar, wait for the records to propagate through resolver caches,
and then verify that the custom address loads with a valid HTTPS certificate.
