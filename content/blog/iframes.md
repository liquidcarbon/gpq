---
description: Embed <iframe>
---

# iframes

That was not a real iframe.  It's only useful for YouTube videos and a [few more things](https://docs.gitbook.com/content-editor/blocks/embed-a-url).

Because:

> MDX supports standard markdown syntax ([CommonMark](https://spec.commonmark.org/current/)). It does not support embeds by default.
>
> —[https://mdxjs.com/guides/embed/](https://mdxjs.com/guides/embed/)

{% embed url="https://covid91.s3.amazonaws.com/covid_weekly_20210802.html" fullWidth="true" %}
Embedded from S3 (not a real iframe).
{% endembed %}


## Feeling lucky

<iframe src="https://covid91.s3.amazonaws.com/covid_weekly_20210802.html" width="720" height="600"></iframe>
<figure><iframe src="https://covid91.s3.amazonaws.com/covid_weekly_20210802.html"></iframe></figure>

Nothing on Gitbook.  In contrast, [Docsify-This](https://docsify-this.net/) [is cool with iframes](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/liquidcarbon/gpq/main/content/blog&homepage=iframes.md&sidebar=true#/).

