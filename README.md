# Cheap KVM VPS: What $0.99/Month Gets You, Which Plan Fits Your Workload, and How Yearly Billing Changes the Real Price (All JustHost Plans Compared)

JustHost's cheapest KVM VPS costs $0.99 for one month. That buys 1 vCPU, 512MB RAM, 5GB NVMe and a 10Mbps unmetered connection, and it comes with a restriction most listicles skip: you can only buy it once, for a single month, and only when no other VPS is running on your account. It exists so you can test the network before paying for a real plan.

The plan most readers should start with is **Sirius: 1 vCPU, 1GB RAM, 20GB NVMe, 300Mbps unmetered, from $2.81/month on annual billing**. That handles a low-traffic WordPress site, a Docker host running a few containers, or a VPN endpoint without strain. Below is every plan JustHost currently lists, what each one is actually good for, and the parts of the cost that don't appear in the headline number.

> **Quick pick:** Sirius at $2.81/mo (annual billing) fits most readers. Need 2GB of RAM for a busier site or a Java app? Arcturus at $4.01/mo. Need 4GB for WooCommerce, multiple sites or a heavier Docker stack? Vega at $7.79/mo.
> 👉 [Check the current Sirius plan price](https://justhost.asia/services/vps/tariffs/sirius?ref=196392)

## The full JustHost plan table

Prices below are the monthly equivalent when you pay annually. JustHost's annual billing runs about 20% below the month-to-month rate; I break that out further down.

| Plan | vCPU | RAM | NVMe | Price (annual billing) | Order |
| --- | --- | --- | --- | --- | --- |
| VPS Promo | 1 | 512MB | 5GB | $0.99 first month only | [Start with the $0.99 trial](https://justhost.asia/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 | 1GB | 10GB | $2.21/mo | [Order New Star](https://justhost.asia/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Double Star | 2 | 2GB | 20GB | $3.90/mo | [Order Double Star](https://justhost.asia/services/vps/tariffs/double-star?ref=196392) |
| Bright Star | 4 | 4GB | 30GB | $5.39/mo | [Order Bright Star](https://justhost.asia/services/vps/tariffs/bright-star?ref=196392) |
| Sirius | 1 | 1GB | 20GB | $2.81/mo | [Order Sirius](https://justhost.asia/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 | 2GB | 30GB | $4.01/mo | [Order Arcturus](https://justhost.asia/services/vps/tariffs/arcturus?ref=196392) |
| Alpha Centauri | 2 | 2GB | 40GB | $5.21/mo | [Order Alpha Centauri](https://justhost.asia/services/vps/tariffs/alpha-centauri?ref=196392) |
| Vega | 2 | 4GB | 80GB | $7.79/mo | [Order Vega](https://justhost.asia/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 | 4GB | 120GB | $10.61/mo | [Order Capella](https://justhost.asia/services/vps/tariffs/capella?ref=196392) |
| Rigel | 4 | 8GB | 200GB | $16.20/mo | [Order Rigel](https://justhost.asia/services/vps/tariffs/rigel?ref=196392) |
| Antares | 5 | 8GB | 300GB | $19.20/mo | [Order Antares](https://justhost.asia/services/vps/tariffs/antares?ref=196392) |
| Betelgeuse | 6 | 12GB | 400GB | $26.40/mo | [Order Betelgeuse](https://justhost.asia/services/vps/tariffs/betelgeuse?ref=196392) |
| Spica | 8 | 16GB | 500GB | $35.40/mo | [Order Spica](https://justhost.asia/services/vps/tariffs/spica?ref=196392) |

Two plan families sit side by side here. The Star series (New Star, Double Star, Bright Star) is older and cheaper per core, with tighter bandwidth and less storage. The named-star series (Sirius through Spica) is the current standard line and what JustHost's configurator builds from.

### Bandwidth, IPs and OS support

All plans are unmetered, but the port speed varies enough to matter:

| Plan group | Port speed | IPv4 | IPv6 |
| --- | --- | --- | --- |
| VPS Promo | 10Mbps | 1 | No |
| New Star | 100Mbps | 1 | 1 |
| Double Star | 200Mbps | 1 | 1 |
| Bright Star | 300Mbps | 1 | 1 |
| Sirius, Arcturus | 300Mbps | 1 | 1 |
| Alpha Centauri | 400Mbps | 1 | 1 |
| Vega | 500Mbps | 1 | 1 |
| Capella through Spica | 750Mbps | 1 | 1 |

Extra IPv4 addresses can be added up to 64 per server. Linux only: Ubuntu, Debian, CentOS, AlmaLinux, Rocky Linux, FreeBSD and RouterOS all install from the panel. There is no Windows option at any tier, so if you need Remote Desktop, JustHost is the wrong shop.

Data centers span 40+ countries. For Asian traffic, Hong Kong, Singapore and Tokyo are the low-latency choices; Los Angeles and Novosibirsk cover US and Russian traffic. You can switch locations after purchase at no cost, and JustHost allows free IP changes up to 50 times per server. DDoS protection is listed as included on every plan rather than sold as an add-on.

## Monthly or yearly: what you actually pay

JustHost prices annual billing at roughly 80% of the monthly rate. On a small plan the gap is pocket change. On a large one it isn't.

Take Vega (2 vCPU, 4GB, 80GB). At $7.79/mo on annual billing, a year costs **$93.48**. Pay month to month and the rate is about $9.74, or **$116.88** over twelve months. The annual discount saves you $23.40.

Now take Spica (8 vCPU, 16GB, 500GB). Annual billing is $35.40/mo, or **$424.80** a year. Monthly billing lands near $44.25/mo, or **$531.00** a year. The gap is **$106.20**.

Two things to keep straight before you pick annual. First, you pay the whole year upfront, so a $424.80 charge hits your card on day one. Second, if you cancel inside the refund window, the refund is on the full prepaid amount, not on a prorated monthly figure. Ask support to confirm the refund terms in writing before you commit to a year, because JustHost's plan pages don't state a money-back period.

If you want to pay monthly, two promo codes circulate for the standard plans: **LET20** and **PROMO20**, both listed as 20% off monthly billing and marked valid through December 31, 2026. They don't apply to VPS Promo, the Star series or special offers. Test the code at checkout; if it's been retired, the cart will tell you before you pay.

## What sits outside the $X/mo figure

The number on the plan card is not the number on your statement. Here is where the extras land for JustHost specifically.

**The $0.99 plan is a one-shot.** VPS Promo cannot be renewed and cannot be bought while another VPS is active on your account. Month two costs at least $2.21 (New Star) or $2.81 (Sirius). If you budget $0.99 as your ongoing cost, you'll be off by roughly 3x.

**10Mbps is a testing speed, not a serving speed.** A 10Mbps port moves about 1.25MB per second at full tilt. Fine for SSH, package installs and checking latency from your region. Not fine for serving a site with images, let alone video. Treat VPS Promo as a network test, nothing more.

**Backups are not documented.** JustHost's plan pages don't mention automated backups or snapshots at any tier. Assume you are responsible for your own backup job until support tells you otherwise, and price in external object storage if the data matters.

**No control panel is bundled.** These are unmanaged servers with root access. cPanel, Plesk and DirectAdmin are not part of the price and aren't listed as purchasable add-ons on the plan pages. If you want a GUI, budget for a panel license separately or run something free like Webmin or Coolify.

**No Windows.** Covered above, but worth repeating because "KVM" often implies "can run any OS." JustHost's KVM guests are Linux and BSD only.

On the positive side, the things hosts usually charge for are free here: location changes, IP changes (up to 50), DDoS filtering, and a custom configurator that starts at $2.37/mo if no preset fits.

## Which plan fits your workload

The rule of thumb from budget-VPS buying guides holds: 1GB for a test box or a tiny site, 2GB for a small WordPress install, 4GB and up for WooCommerce or multiple sites. Map that onto JustHost's lineup:

**Learning Linux, testing latency, running a throwaway project** → VPS Promo at $0.99 for one month, then move to New Star at $2.21 if you want to keep it. Don't put anything public on a 10Mbps port.

**One low-traffic WordPress site, a personal blog, a single Docker container** → Sirius at $2.81. The 20GB of NVMe covers the OS, the stack and a few months of uploads. This is the plan that fits the largest share of readers.

**A WordPress site with real traffic, a small Postgres instance, a handful of Docker services** → Arcturus at $4.01 for the extra 1GB of RAM, or Alpha Centauri at $5.21 if you want two cores and 40GB instead.

**WooCommerce, multiple sites on one box, a CI runner, a medium Docker stack** → Vega at $7.79. The 80GB of NVMe is the real reason to pick it over Bright Star; 30GB fills up fast once you have a database and a few site backups.

**Elasticsearch, a large database, a game server, anything memory-hungry** → Rigel at $16.20 (8GB) is the first tier that makes sense. Betelgeuse at $26.40 doubles storage to 400GB.

**Spica at $35.40 is overkill for almost everyone reading this.** Eight cores and 16GB is a small production cluster, not a personal VPS. If you're eyeing it for a single site, you're buying capacity you won't use.

One oddity worth flagging: **Bright Star (4 vCPU, 4GB, 30GB, $5.39) is cheaper than Vega (2 vCPU, 4GB, 80GB, $7.79)**. You trade 50GB of storage and 200Mbps of port speed for two extra cores and $2.40/mo. If your workload is CPU-bound and storage-light, Bright Star wins. If it's storage-bound, Vega does.

## Who shouldn't buy a KVM VPS at all

Four groups should close this tab.

**Anyone whose budget is below shared hosting.** A $2–3/mo shared plan includes a panel, email and support. A $2.81 KVM VPS includes none of those. You're paying the same money for more control and more work.

**Anyone without basic Linux skills.** JustHost is unmanaged. If `systemctl` and `ufw` aren't familiar, you'll spend your first week firefighting instead of building. A managed VPS costs more but saves the time.

**Anyone running a single static site.** Shared hosting or a static host is cheaper, faster to set up and needs no maintenance. KVM earns its keep when you need root, custom software or isolation.

**Anyone with a short, predictable project.** A three-week scraping job or a demo that runs for a month belongs on hourly cloud billing, not a monthly or annual VPS contract.

## How JustHost compares on price

Same-class hardware varies wildly across the budget KVM market. Here's what the entry tiers look like against JustHost:

| Provider | Entry price | Entry specs | Billing |
| --- | --- | --- | --- |
| JustHost | $0.99 first month, $2.21+ ongoing | 512MB–1GB RAM, 5–10GB NVMe, 10–100Mbps unmetered | Monthly or annual |
| InterServer | $3.00/mo | 2GB RAM, 30GB SSD, 2TB transfer per slice | Monthly |
| Ucartz | $10.00/mo ($36/yr) | 4GB RAM, 50GB NVMe, unmetered, US only | Monthly or annual |
| Koddos | $12.95/mo | 512MB RAM, 10GB RAID-10, 250GB bandwidth, 5 locations | Monthly |

Compare the 1GB tier directly. JustHost's Sirius gives you 1GB RAM and 20GB NVMe for $2.81/mo. Koddos charges $19.95/mo for 1GB RAM and 20GB of RAID-10 storage. That's roughly seven times the price for the same RAM and disk. JustHost's advantage sits in bandwidth (unmetered versus 500GB) and location count; Koddos counters with RAID-10 and a wider choice of Asian and European sites.

Against InterServer, the comparison flips. InterServer's $3/mo gets you 2GB of RAM and 30GB of SSD, which beats JustHost's Arcturus at $4.01 for 2GB and 30GB. InterServer bills monthly with no annual lock-in and offers optional cPanel. If 2GB is your floor and you want a panel, InterServer is the better buy. If you want unmetered bandwidth, more Asian locations or a sub-$1 entry point, JustHost wins.

## Before you check out

Four things to confirm, because JustHost's plan pages don't answer them:

1. **Refund window and exclusions.** No money-back period is stated on the plan pages. Ask support for the number of days and what isn't refundable before you pay for a year.
2. **Renewal price.** Confirm that the annual rate you're quoted is the rate you'll pay next year, not a first-term discount that resets upward.
3. **Backups.** Ask whether automated backups exist, what they cost, and how restores work. If the answer is "you handle it," set up a cron job to object storage on day one.
4. **Provisioning time.** Some budget hosts hold orders for fraud review for days. Ask whether your server is deployed instantly after payment or queued for manual approval, especially if you're paying from a region the billing team flags.

## Final call

Match the plan to the job and nothing else:

- Testing the network, learning Linux → **VPS Promo ($0.99, one month)**.
- One small site, one container, a VPN → **Sirius ($2.81)**.
- 2GB needed for a real workload → **Arcturus ($4.01)** or InterServer if you want monthly billing and a panel.
- 4GB for WooCommerce or multiple sites → **Vega ($7.79)**, or **Bright Star ($5.39)** if you're CPU-bound and can live with 30GB.
- 8GB+ for databases or memory-heavy apps → **Rigel ($16.20)**.

Confirm the refund terms and renewal price before you commit to annual billing. Those two answers decide whether a cheap KVM VPS stays cheap in year two.

👉 [See all JustHost KVM VPS plans and current pricing](https://justhost.asia/?ref=196392)
