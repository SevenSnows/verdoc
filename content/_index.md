+++
title = "Introduction"
description = ""
date = "2017-04-24T18:36:24+02:00"

+++

# VerDoc - Versioned Documentation

VerDoc achieves version specific dcumentation for software; VerDoc is a process; it combines Hugo (fast-static generation of HTML pages/sites) with version numbered deployment directories. 

Hence 

{{% panel theme="success" header="Versioned documentation" footer="Simplifying versioned documentation for software releases" %}}

* Version 1.0.x is published into 
 * /v1.0
* Version 1.1.x is published into 
 * /v1.1
* /Latest is always the latest version!
* Javascript is used to advise users of the link to the "latest version"

{{% /panel %}}


## Built on
VerDoc as a process is built on :

* Hugo - [https://gohugo.io/] - A brilliant static generator
* DocDocK Theme - [https://github.com/vjeantet/hugo-theme-docdock] & [http://docdock.netlify.com/] - A great theme for documentation
* Powershell
* Continous integration - expand

And its purpose to enable teams to 

* Simply maintain documentation in MarkDown
* Allow for publishing at little to no effort, whilst ensuring old versions of documentation are available.

We may also like to explore

{{% panel theme="success" header="Automated deployments" footer="Netlify builds, deploys, and hosts  frontends." %}}
Automatically published and hosted thanks to [Netlify](https://www.netlify.com/).

Read more about [Automated HUGO deployments with Netlify](https://www.netlify.com/blog/2015/07/30/hosting-hugo-on-netlifyinsanely-fast-deploys/)
{{% /panel %}}

