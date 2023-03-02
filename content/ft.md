---
title: "Vedant Andhale"
enableToc: false
---

# Button

{{< button relref="/" >}}Get Home{{< /button >}}
{{< button href="https://github.com/alex-shpak/hugo-book" >}}Contribute{{< /button >}}


# Details


{{< details "Title" open >}}
## Markdown content
Lorem markdownum insigne...
{{< /details >}}

{{</* details title="Title" open=true */>}}
## Markdown content
Lorem markdownum insigne...
{{</* /details */>}}

# Expand

{{< expand >}}
## Markdown content
Lorem markdownum insigne...
{{< /expand >}}

# tabs

{{< tabs "uniqueid" >}}
{{< tab "MacOS" >}} # MacOS Content {{< /tab >}}
{{< tab "Linux" >}} # Linux Content {{< /tab >}}
{{< tab "Windows" >}} # Windows Content {{< /tab >}}
{{< /tabs >}}

{{< tabs "uniqueid" >}}
{{< tab >}} # Project {{< /tab >}}
{{< button relref="/"  >}}Get Home{{< /button >}}
{{< button href="https://github.com/alex-shpak/hugo-book" >}}Contribute{{< /button >}}
{{< /tabs >}}
{{< tabs "uniqueid" >}}
{{< tab >}} # Project {{< /tab >}}
{{< button relref="/">}}Get Home{{< /button >}}
{{< button href="https://github.com/alex-shpak/hugo-book" >}}Contribute{{< /button >}}
{{< /tabs >}}

# calloutes

> [!info]
> Here's a callout block.
> It supports **Markdown**, [[Internal link|Wikilinks]], and [[Embed files|embeds]]!

> [!tip] Callouts can have custom titles
> Like this one.


> [!faq]- Are callouts foldable? use -/+
> Yes! In a foldable callout, the contents are hidden when the callout is collapsed.

> [!question] Can callouts be nested?
> > [!todo] Yes!, they can.
> > > [!example]  You can even use multiple layers of nesting.

> [!success]
> Lorem ipsum dolor sit amet

> [!warning]
> Lorem ipsum dolor sit amet

> [!failure]
> Lorem ipsum dolor sit amet

> [!danger]
> Lorem ipsum dolor sit amet

> [!bug]
> Lorem ipsum dolor sit amet

> [!example]
> Lorem ipsum dolor sit amet

> [!quote]
> Lorem ipsum dolor sit amet
