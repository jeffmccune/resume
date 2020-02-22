---
title: Jeff McCune
layout: resume
---

# Jeff McCune

_[github.com/jeffmccune](https://github.com/jeffmccune) &middot; jeff@openinfrastructure.co &middot; Portland, OR &middot; 669.444.1014_

### Experience

##### [Open Infrastructure Services](https://openinfrastructure.co)

> **Founder & Principal Consultant (Sep 2015 - Present)** - Advised clients on
> service deployment automation, DevOps and Cloud Infrastructure automation.
> Grew and managed all aspects of the business, including employees and
> partnerships.  Planned and led multiple company-wide datacenter migrations to
> Google Cloud.  Invented small command line tools to fill product gaps in
> Google Cloud Platform and Puppet Enterprise.  Delivered customer solutions
> including:

>  * [puppet_sync][puppet_sync] - Implementation of [Code
>    Manager][code_manager] Puppet Enterprise functionality for a large Puppet open
>    source customer.
>  * [ncio][ncio] - Increase availability of Puppet Enterprise by replicating
>    the node classifier service.
>  * [vpc-link][vpc-link] - Overcome Google Cloud VM limits per VPC network.
>  * [VM DNS Garbage Collector][vm-dns-gc] - Automatically clean up DNS records
>    in response to VM termination audit log events.
>  * [Scarab][scarab] - Automatically create presistent Cloud VPN tunnels using
>    ipsec and BGP on an EdgeRouter-4 device with a dynamic IP address.
>  * [F5 Map][f5map] - Parse F5 iRules and output structured JSON and CSV for
>    analysis and migration to Cloud firewalls.
>  * [Cloud Foundation Toolkit][cft] - Accerlate enterprise adoption of Google
>    Cloud with ready to use Terraform modules.  Designed and implemented the
>    address and startup-scripts modules, contributed to the project-factory
>    module.

##### [Puppet, Inc.](https://puppet.com/)

> **Senior Software Engineer (May 2011 - Sep 2015)** - Led the team responsible
> for peer reviewing all open source contributions to [Puppet][puppet-code].
> Brought Puppet to Windows and Solaris, which expanded the enterprise market.
> Built the automated tooling and first set of packages for Puppet Enterprise
> which led to annual recurring revenue and sustained company growth.  Created
> the [Puppet standard library][stdlib] module which has over 100 million
> installations and is included in the Puppet Enterprise product.

> **Professional Service Engineer**  (May 2010 - May 2011) Accelerated the
> adoption of Puppet.  Scaled a large social network company's Puppet
> deployment to 45,000+ servers.  Designed and implemented a REST API caching
> solution resulting in an order of magnitude reduction in the number of
> servers from ~100 to 8.  The solution achieved a greater than 99% cache hit
> rate resulting in reduced load on backend REST API services.  Published the
> design in [Pro Puppet][Pro Puppet] and productized the design in Puppet
> Enterprise.

##### [Netsmart Technologies](https://www.ntst.com)

> **SaaS Manager (Jul 2009 - May 2010)** - Managed the Avatar On Demand SaaS
> Product.  Automated the deployment and setup of Avatar for new SaaS customers,
> dramatically reducing the time between closed sale and successful
> implementations.  Leveraged Puppet and custom written Python tools to reduce
> cost and error rates.

> **Senior Systems Administrator (Apr 2008 - Jul 2009)** - Automated backups,
> managed the storage infrastructure, virtualization infrastructure with Solaris
> Zones, Xen and VMware, network layer.

##### [The Ohio State University](https://www.osu.edu)

> **Systems Administrator (Mar 2004 - Mar 2008)** - Provide technical support to
> faculty, staff and graduate students at the Department of Mathematics.
> Developed, deployed and maintained network services and infrastructure.
> Managed student employees.  Designed and implemented a configuration
> management system using Puppet which replaced cfengine in the network.

> **Systems Specialist (Jul 2002 - Mar 2004)** - Provided technical support to
> faculty, staff and graduate students at the Department of Linguistics.
> Maintained, documented and deployed new IT services. Wrote custom software for
> use by researchers.

### Education

> **Bachelor of Science in Computer Science & Engineering - [The Ohio State University](http://www.osu.edu/)**

### Miscellany

> * Co-Author of [Pro Puppet][Pro Puppet].
> * Certified Google Cloud Professional Architect (2018-2020).
> * Invited Speaker at Apple WWDC, MacConf, PuppetConf (multiple), DevOps Days (multiple).

### Fit

> I'm a senior developer with a strong background in systems administration and
> operations.  I'm well suited to design and architect solutions to technical
> challenges which span multiple teams in an organization.  Examples include
> cloud networking, automated software delivery platforms, automated
> infrastructure delivery using Terraform, and automated configuration
> management.

----

_This document lives at [jeffmccune.github.io/resume][resume]_

[Pro Puppet]: http://www.apress.com/us/book/9781430230571
[ncio]: https://github.com/jeffmccune/ncio
[crossfader]: https://github.com/puppetlabs/crossfader
[resume]: https://jeffmccune.github.io/resume/
[puppet-code]: https://github.com/puppetlabs/puppet
[puppet_sync]: https://docs.google.com/document/d/1MhwmiKQDGjznkaNRVh7S1IdU2hQUYHtHCemckz77aSE/preview?usp=sharing
[code_manager]: https://puppet.com/docs/pe/latest/code_mgr.html
[vpc-link]: https://github.com/openinfrastructure/terraform-google-vpc-link
[scarab]: https://github.com/openinfrastructure/scarab
[vm-dns-gc]: https://github.com/GoogleCloudPlatform/professional-services/tree/master/examples/gcf-pubsub-vm-delete-event-handler
[f5map]: https://github.com/GoogleCloudPlatform/professional-services/pull/169
[cft]: https://cloud.google.com/foundation-toolkit/
[stdlib]: https://forge.puppet.com/puppetlabs/stdlib
