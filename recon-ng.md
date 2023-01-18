# recon-ng  

To run.  

`recon-ng`  

Search the market place for term github.  

`marketplace search github`  

To learn more about a mmodule.  

`marketplace info /recon/domains-hosts/google_site_web`  

Install module.  

`marketplace install /recon/domains-hosts/google_site_web`  

Load module.  

`marketplace load /recon/domains-hosts/google_site_web`  

Display details.  

`info`  

Set target domain.  

`options set SOURCE fake-company.com`  

At default prompt, show framework items.  

`show`  

Lookup hosts in database.  

`show hosts`  

Find ip addresses on these hosts.  

```
marketplace info /recon/hosts-hosts/resolv
marketplace install /recon/hosts-hosts/resolv
modules load /recon/hosts-hosts/resolv
run
```
