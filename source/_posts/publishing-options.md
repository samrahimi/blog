---
title: Publishing options
tags: Getting Started
author:
  name: Ghost
  slug: /author/ghost
date: 2018-08-20 11:12:04
---

<h2 id="distribute-your-content">Distribute your content</h2><p>Access the post settings menu by clicking the settings icon in the top right hand corner of the editor and discover everything you need to get your content ready for publishing. This is where you can edit things like tags, post URL, publish date and custom meta data.</p><h2 id="feature-images-url-excerpts">Feature images, URL &amp; excerpts</h2><p>Insert your post feature image from the very top of the post settings menu. Consider resizing or optimising your image first to ensure it's an appropriate size. Below this, you can set your post URL, publish date and add a custom excerpt.</p><h2 id="tags-authors">Tags &amp; authors</h2><p>You can easily add multiple tags and authors to any post to filter and organise the relationships between your content in Ghost.</p><h2 id="structured-data-seo">Structured data &amp; SEO</h2><p>There's no need to hard code your meta data. In fact, Ghost will generate default meta data automatically using the content in your post.</p><p>Alternatively, you can override this by adding a custom meta title and description, as well as unique information for social media sharing cards on Facebook and Twitter.</p><p>It's also possible to set custom canonicals, which is useful for guest posts or curated lists of external links.</p><p>Ghost will automatically implement <strong>structured data</strong> for your publication using JSON-LD to further optimise your content.</p><pre><code>{
    "@context": "https://schema.org",
    "@type": "Article",
    "publisher": {
        "@type": "Organization",
        "name": "Publishing options",
        "logo": "https://static.ghost.org/ghost-logo.svg"
    },
    "author": {
        "@type": "Person",
        "name": "Ghost",
        "url": "http://demo.ghost.io/author/ghost/",
        "sameAs": []
    },
    "headline": "Publishing options",
    "url": "http://demo.ghost.io/publishing-options",
    "datePublished": "2018-08-08T11:44:00.000Z",
    "dateModified": "2018-08-09T12:06:21.000Z",
    "keywords": "Getting Started",
    "description": "The Ghost editor has everything you need to fully optimise your content. This is where you can add tags and authors, feature a post, or turn a post into a page.",
    }
}
    </code></pre><p>You can test that the structured data <a href="https://schema.org/">schema</a> on your site is working as it should using <a href="https://search.google.com/structured-data/testing-tool" rel="noreferrer nofollow noopener">Google’s structured data tool</a>. </p><h2 id="code-injection">Code injection</h2><p>This tool allows you to inject code on a per post or page basis, or across your entire site. This means you can modify CSS, add unique tracking codes, or add other scripts to the head or foot of your publication without making edits to your theme files. </p><p><strong>To add code site-wide</strong>, use the code injection tool in the main admin menu. This is useful for adding a Google Analytics tracking code, or to start tracking with any other analytics tool.</p><p><strong>To add code to a post or page</strong>, use the code injection tool within the post settings menu. This is useful if you want to add art direction, scripts or styles that are only applicable to one post or page.</p><h2 id="next-admin-settings">Next: Admin settings</h2><p>Now you understand how to create and optimise content, let's explore some <a href="https://demo.ghost.io/admin-settings/">admin settings</a> so you can invite your team and start collaborating.</p>