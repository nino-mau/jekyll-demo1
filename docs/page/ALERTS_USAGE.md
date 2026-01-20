# GitHub-Style Alerts Usage

This site now supports GitHub-style alerts/notes with **icons displayed inline with titles**. Here's how to use them:

## Syntax

Use HTML `<div>` elements with the appropriate class:

```html
<div class="alert alert-note">
<p><strong>Note</strong></p>
<p>This is a note with useful information.</p>
</div>
```

**Note:** The icon appears automatically before the title (first paragraph) on the same line using CSS `::before` pseudo-element.

## Available Alert Types

### Note (Blue)
<div class="alert alert-note">
<p><strong>Note</strong></p>
<p>Useful information that users should know, even when skimming content.</p>
</div>

```html
<div class="alert alert-note">
<p><strong>Note</strong></p>
<p>Your note text here.</p>
</div>
```

### Tip (Green)
<div class="alert alert-tip">
<p><strong>Tip</strong></p>
<p>Helpful advice for doing things better or more easily.</p>
</div>

```html
<div class="alert alert-tip">
<p><strong>Tip</strong></p>
<p>Your tip text here.</p>
</div>
```

### Important (Purple)
<div class="alert alert-important">
<p><strong>Important</strong></p>
<p>Key information users need to know to achieve their goal.</p>
</div>

```html
<div class="alert alert-important">
<p><strong>Important</strong></p>
<p>Your important text here.</p>
</div>
```

### Warning (Yellow/Orange)
<div class="alert alert-warning">
<p><strong>Warning</strong></p>
<p>Urgent info that needs immediate user attention to avoid problems.</p>
</div>

```html
<div class="alert alert-warning">
<p><strong>Warning</strong></p>
<p>Your warning text here.</p>
</div>
```

### Caution/Danger (Red)
<div class="alert alert-caution">
<p><strong>Caution</strong></p>
<p>Advises about risks or negative outcomes of certain actions.</p>
</div>

```html
<div class="alert alert-caution">
<p><strong>Caution</strong></p>
<p>Your caution text here.</p>
</div>
```

## Multiple Paragraphs

You can include multiple paragraphs:

<div class="alert alert-note">
<p><strong>Note</strong></p>
<p>First paragraph with important information.</p>
<p>Second paragraph with more details.</p>
</div>

```html
<div class="alert alert-note">
<p><strong>Note</strong></p>
<p>First paragraph.</p>
<p>Second paragraph.</p>
</div>
```

## With Code

<div class="alert alert-tip">
<p><strong>Tip</strong></p>
<p>To automatically bind the widget to your map, drag and drop it onto the map widget.</p>
<p>You can also use inline code like <code>bundle exec jekyll serve</code>.</p>
</div>

## Dark Mode

All alerts automatically adapt to dark mode using the `prefers-color-scheme` media query!
