# How much should a cloud VPS cost? $6.58 to $45 a month, which plan size fits your workload, and the billing details worth checking before you order

A 1 vCPU / 2 GB cloud VPS with 60 GB of storage lists at $11 a month at Liquid Web. Contabo sells 4 vCPU / 6 GB for €4.50 a month, and its US 8 GB plan shows $6.58 a month for the first 24 months against a standard $7.90. SpinServers' VPS range starts at 6 vCPU / 8 GB, with $45.00 USD a month published for the 8 vCPU / 8 GB configuration.

That puts the working range for a general-purpose cloud VPS somewhere between roughly $5 and $45 a month, and the spread has surprisingly little to do with core count. What follows covers which size handles which job, how "starting at" prices get flattered, and the four line items that move the real monthly total.

> **Quick answer.** If your workload needs 8 vCPU, 8 GB RAM, a 1 Gbps port and 10 TB of monthly transfer, the SpinServers KVM 8 vCPU plan is listed at $45.00 USD per month and is the one to open first. If you need a 1–2 GB box for a single site, this lineup has nothing that small; Contabo (€4.50/mo) and Liquid Web ($11/mo) do.
>
> 👉 [See the current SpinServers VPS configurations and listed prices](https://bit.ly/Spinservers)

## SpinServers cloud VPS plans

The VPS side of SpinServers is a short catalogue, split into Simple and Advanced Application Servers. Every plan is KVM-based with DDR4 memory, RAID-10 SSD storage and a 1 Gbps network port.

| Plan | vCPU / RAM | Storage | Monthly transfer | Listed price | Order |
| --- | --- | --- | --- | --- | --- |
| Simple Application Server | 6 vCPU / 8 GB | 120 GB RAID-10 SSD | 8 TB | Not listed | [Check current price](https://bit.ly/Spinservers) |
| KVM 8vCPU 8GB | 8 vCPU / 8 GB | 160 GB RAID-10 SSD | 10 TB | $45.00 USD/mo | [Check current price](https://bit.ly/Spinservers) |
| KVM 12vCPU 12GB | 12 vCPU / 12 GB | 160 GB RAID-10 SSD | 10 TB | Not listed | [Check current price](https://bit.ly/Spinservers) |
| KVM 16vCPU 16GB | 16 vCPU / 16 GB | 320 GB RAID-10 SSD | 15 TB | Not listed | [Check current price](https://bit.ly/Spinservers) |
| KVM 32vCPU 32GB | 32 vCPU / 32 GB | 500 GB SSD | 20 TB | Not listed | [Check current price](https://bit.ly/Spinservers) |

Every plan includes one IPv4 and one IPv6 address. The 16 vCPU and 32 vCPU configurations are listed as Intel Xeon hardware.

Two things about that table are worth knowing before you shortlist on price. The first is that only one plan carries a public starting price. The other four are published by configuration and priced at order time, so a like-for-like comparison against a provider with a fixed grid takes one extra step.

The second is outbound email. Port 25 is closed by default on every SpinServers VPS. You can ask for it to be opened with a ticket explaining the use case, and the request can be refused. If a contact form, invoice mail or password reset flow depends on the server sending mail, plan for an external SMTP relay or get the port opened before you migrate anything.

The smallest plan here is 6 vCPU / 8 GB. There is no 1 GB or 2 GB entry tier, which is the single most important fact if you arrived from a search for cheap cloud VPS hosting: this is a mid-range lineup, priced accordingly.

👉 [Check the full SpinServers VPS plan list and current pricing](https://bit.ly/Spinservers)

## What the rest of the market charges

These are current, published prices from other providers, useful as an anchor when you compare the table above. No links, no promotions, just the numbers as displayed.

| Provider | Plan | Specs | Price |
| --- | --- | --- | --- |
| Contabo | Cloud VPS 1 | 4 vCPU / 6 GB / 100 GB NVMe or 200 GB SSD | €4.50/mo |
| Contabo | Cloud VPS 4 (US) | 4 vCPU / 8 GB / 100 GB SSD | $7.90/mo, $6.58 for the first 24 months |
| Liquid Web | Compute 1 | 1 vCPU / 2 GB / 60 GB / 2 TB | $11/mo ($0.015/hr) |
| Contabo | Cloud VPS 8 (US) | 8 vCPU / 24 GB / 300 GB SSD | $20.85/mo, $17.49 for the first 24 months |
| Liquid Web | Compute 4 | 4 vCPU / 8 GB / 240 GB / 5 TB | $45/mo ($0.062/hr) |

At the $45 mark the trade is visible. Liquid Web gives you 4 vCPU, 8 GB RAM, 240 GB of storage and 5 TB of transfer for $45 a month. SpinServers gives 8 vCPU, 8 GB RAM, 160 GB of RAID-10 storage and 10 TB for the same $45.00. If the workload is CPU-bound (build jobs, game servers, encoding, scraping), the extra cores and transfer are worth more than the storage. If you are storing media or running large databases, 160 GB will be the constraint that sends you back to the pricing page in three months.

Contabo undercuts both at the same core count, and the gap between $17.49 and $45 buys a lot of patience for a provider whose support is thinner. The catch is in the term, which the next section covers.

## How "starting at" cloud VPS prices get flattered

Liquid Web's VPS page headline says hosting starts at $5/mo. The Cloud VPS table on that same page bottoms out at $11/mo for 1 vCPU, 2 GB RAM, 60 GB storage and 2 TB of bandwidth. The $5 figure belongs to something other than the Cloud VPS grid. Read the table, not the headline.

Contabo does the opposite, publishing both numbers. Its US page shows $6.58 prominently and $7.90 as the standard rate; the 8 vCPU plan shows $17.49 against $20.85. The smaller figure is the effective monthly rate for the first 24 months of a term commitment, and the standard rate is what you pay afterwards. Those prices are also quoted as effective monthly rates on a 12-month subscription including applicable taxes, which is a different animal from a month-to-month list price.

A reusable three-question check when you hit any "from $X" claim:

1. Which plan is the price attached to? The cheapest row in the grid, or a different product with a similar name?
2. What term is the price tied to? Monthly, 12 months, 24 months?
3. What does the same plan cost after the promotional period, and is there an hourly rate if you only need it for a week?

Liquid Web lists the hourly rate beside each monthly figure ($0.015/hr on the $11 plan), which is genuinely useful if you need a box for a migration window rather than a year.

## Which cloud VPS size to buy

**1–2 GB of RAM.** A static site, a small blog behind a cache, a monitoring agent, a WireGuard endpoint. Liquid Web's Compute 1 at $11/mo covers this with 60 GB of storage and 2 TB of transfer. Note that Windows changes the maths: a 2023 snapshot of Atlantic.Net's pricing page showed its 2 GB plan at $8.00/mo on Linux and $15.50/mo on Windows, and that page is old enough to treat as a shape rather than a quote. The pattern holds across the market.

**4–8 GB of RAM.** WordPress with a database and a handful of plugins, a small SaaS with a background worker, Docker running four or five containers. Liquid Web's 2 vCPU / 4 GB / 80 GB plan at $17/mo and its 4 vCPU / 8 GB / 240 GB plan at $45/mo bracket this tier. Contabo's 4 vCPU / 8 GB lands at $7.90 standard, which is the cheapest verified entry into it.

**16 GB and up.** Several projects on one box, a game server, CI runners, an analytics stack. Contabo's 16 vCPU / 64 GB / 500 GB plan is $55.10 standard or $46.20 for the first 24 months; Liquid Web's 6 vCPU / 16 GB / 440 GB is $90/mo. SpinServers' 16 vCPU / 16 GB with 15 TB of transfer sits in this bracket by core count with less RAM than the Contabo equivalent, which tells you it is aimed at compute-heavy, memory-light jobs.

A cloud VPS shares the underlying host with other instances, so the RAM and CPU in the table are your ceiling, not a dedicated machine's floor. Workloads that spike hard (video encoding, large MySQL imports, game server tick rates) hit that ceiling faster than the plan name suggests, which is why the 8 vCPU / 8 GB ratio at SpinServers makes sense for parallel jobs and very little sense for a single fat database.

## Four items that change the monthly total

### Upgrades take one click. Downgrades take a migration.

OVHcloud states this plainly: you can move a VPS to a larger configuration in one click, but only within the same datacenter, and direct migration between configurations is not available in the downward direction. Downgrading means ordering the smaller plan, moving your data yourself and cancelling the old service.

So "start small and grow" is a valid strategy on that platform; "start big and shrink if it's overkill" is not. Ask about the downgrade path before you buy the 16 GB plan you suspect you don't need.

### "Unlimited traffic" is a rate limit, not a licence

Contabo describes inbound traffic as unlimited and unmetered, and outbound traffic as unlimited under a fair usage policy, with the right to throttle servers showing exceptionally high or disruptive usage. That is not the same promise as a hard quota.

OVHcloud's Asia-Pacific locations (Mumbai, Singapore, Sydney) publish real quotas: 500 GB on VPS-1, 1 TB on VPS-2 and VPS-3, 3 TB on VPS-4, throttled to 10 Mbit/s once you exceed them. A 10 Mbit/s cap turns a busy site into a slow one without warning. Check both numbers on any plan you shortlist: the quota, and what happens when you cross it.

### Windows and control panels are separate line items

On Contabo's Cloud VPS 1 at €4.50, Windows Server adds €7.15/mo, Plesk on Linux adds €13.50/mo and cPanel adds €23.50/mo. cPanel alone costs more than five times the server it runs on. If your stack needs a panel, price the bundle, not the box.

OVHcloud's Local Zone VPS goes the other way and removes the choice: Linux distributions only, with no Windows, Plesk, cPanel or Docker support on those locations.

### Backups are included, manual, or an add-on

OVHcloud includes a daily backup on its current VPS range: the VPS is backed up every day on a 7-day rolling window, exported and replicated three times inside the same datacenter, then made available in the client area. Snapshots and external backup are optional extras on top.

Contabo ships 1 to 3 snapshots depending on the plan, with automatic backup as a paid add-on. Snapshots are manual and point-in-time, which is fine before an upgrade and useless if you discover corruption three weeks later.

A €4.50 plan with paid backup and cPanel is no longer a €4.50 plan, and a $45 plan without any backup is a $45 plan plus a recovery incident.

👉 [See what each SpinServers VPS plan includes before you total it up](https://bit.ly/Spinservers)

## FAQ

**Is a cloud VPS different from a VPS?**
Mostly marketing. Both are virtual machines on shared hardware. "Cloud" usually signals hourly billing, resize-in-place and a provider-managed pool of hosts. The differences that matter to a buyer show up in the details: whether you can resize upward without reinstalling, whether a daily backup is included, whether traffic is metered. Liquid Web's own blog describes cloud VPS instances as sharing the parent server's resources, which is the same constraint every VPS has.

**Is 1 GB of RAM enough?**
For a static site or a cached blog, yes. For WordPress with a database and several plugins on the same machine, 2 GB is the safer floor. SpinServers doesn't sell anything below 8 GB, so this question only applies if you're shopping elsewhere.

**Can I pay month to month?**
Contabo's minimum first contract is one month, though its advertised prices are effective monthly rates on a 12-month subscription and its US promotion runs for 24 months. Liquid Web lists monthly and hourly rates side by side. Confirm the term before you compare a promotional rate to someone else's monthly list price.

**Do I manage the server myself?**
On unmanaged plans, yes: operating system patches, firewall, application stack, migrations. OVHcloud says outright that running a VPS requires basic server administration. Liquid Web sells management tiers on top of the same Cloud VPS configurations if you'd rather not.

**Does a 1 Gbps port mean 1 Gbps of guaranteed throughput?**
No. Port speed is the link's capability. The monthly quota and the provider's fair-use rules decide how much you can actually push through it, and several providers reserve the right to throttle.

## What to pick

One site with modest traffic and a $10 budget: Liquid Web Compute 1 at $11/mo, or Contabo's Cloud VPS 1 at €4.50 if you can live with thinner support and a euro invoice.

Maximum cores and RAM per dollar: Contabo, with the promotional term read carefully before checkout.

8 vCPU, 10 TB of transfer, a 1 Gbps port, IPv6 and KVM in a US location: the SpinServers KVM 8 vCPU plan at $45.00 USD per month, with the caveat that the other four sizes in the lineup need a quote before you can rank them.

Then confirm two things before the card comes out. First, the price for the exact plan and term you'll actually buy, including what it becomes after any introductory period. Second, whether backup, Windows and a control panel are inside that number or added on top; on cheap plans those three items routinely double the bill.

👉 [Open the SpinServers VPS page to confirm the plan and price for your configuration](https://bit.ly/Spinservers)
