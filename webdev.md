Honestly mate, if I were **Phil in 2026**, doing websites as a side business rather than trying to build an agency with dozens of junior developers, I'd optimise for:

* Low maintenance
* Predictable updates
* Fast hosting
* Good SEO
* Not getting called at 9pm because somebody dragged a widget somewhere

Not necessarily what is fashionable.

## What I'd avoid

I probably wouldn't build every site in WordPress anymore.

Not because WordPress is bad.

Because most small business websites don't actually need a CMS.

Think about the average client:

* Home
* About
* Services
* Contact
* Maybe a blog

The content changes once every six months.

That's not really a CMS problem.

That's a "send Phil an email" problem.

***

## My likely stack

### Option 1: Astro (my favourite)

I'd seriously look at Astro.

You get:

* Static output
* Incredible performance
* Markdown support
* Components
* Modern tooling
* Cheap hosting

The sites are basically just files at the end.

Host them almost anywhere.

```text
Astro
Tailwind
Markdown
Cloudflare
GitHub
```

Done.

For a brochure website this is honestly fantastic.

***

### Option 2: Laravel + Statamic

If you still enjoy Laravel.

Statamic is probably the CMS I'd choose over WordPress these days.

It gives you:

* Flat file content
* Control
* Flexible CMS editing
* Very little plugin madness

You still get a CMS when clients genuinely need one.

Think of it as:

> "What if Laravel and WordPress had a sensible child?"

***

### Option 3: WordPress for specific use cases

I wouldn't abandon WordPress entirely.

I'd use it when:

* Ecommerce
* Lots of content
* Multiple editors
* Marketing teams
* Daily updates

Then I'd probably use:

```text
WordPress
ACF Pro
GeneratePress
Minimal plugins
MainWP
```

and keep things fairly locked down.

***

## MainWP is actually a strong argument

This is the bit that keeps pulling me back towards WordPress.

From a business perspective:

One dashboard.

* Plugin updates
* Theme updates
* Backups
* Monitoring
* Uptime checks

Across 20-50 client sites.

That's genuinely useful.

You don't get that same ecosystem with many static site generators.

MainWP is one of the things WordPress still does really well.

***

## What I think has happened to us old web developers

I started in a similar era.

Back then websites were:

```text
HTML
CSS
A few images
Upload via FTP
```

Then everything became:

```text
CMS
Database
Plugins
Editors
Page builders
```

And now we're kind of circling back.

Not all the way.

But a lot of developers have realised:

> Maybe a website doesn't need a database, admin system, API, visual editor, JavaScript framework and twenty plugins.

A lot of modern static site generators are really just:

> FrontPage/Dreamweaver philosophy with modern tooling.

Build the site.

Deploy the files.

Serve the pages.

Done.

***

## If it were my money

For a side business I'd probably standardise on:

### 80%

```text
Astro
Tailwind
Markdown
Cloudflare Pages
```

For local businesses and brochure sites.

### 15%

```text
Laravel
Statamic
```

For clients that genuinely need editing capability.

### 5%

```text
WordPress
WooCommerce
MainWP
```

For ecommerce or clients who absolutely must have WordPress.

That gives you:

* Fast sites
* Cheap hosting
* Minimal maintenance
* Less security risk
* Still a CMS option when needed

And perhaps most importantly:

You spend your time building websites rather than maintaining WordPress installations.

Given everything you've said about performance, ACF, controlling layouts, and clients breaking things, I genuinely think you'd feel more at home in the Astro/Statamic world than in the modern "everything is editable blocks" WordPress world. WordPress has improved a lot, but your natural instincts sound much closer to "developer-controlled static site with sensible content editing" than "marketing department can redesign the homepage on a Friday afternoon." 😄
