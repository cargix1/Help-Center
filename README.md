# Help-Center

### Titles and headings
First word capitalized and the rest lowercase.

### Banners

1. Within your article add the following code

```
<div class="banner" data-heading="Lorem ipsum dolor" data-status="warning">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur quis feugiat libero, vitae commodo lacus.
</div>
```

2. Replace the `data-heading` with the heading for the banner

3. Replace the loren ipsum with the content for the banner

4. The `data-status` can either be "info" or "warning"


### Code examples 

All code examples should be contained within a <textarea class="codePreview"></textarea>

```
<textarea class="codePreview" rows="1">{% include 'storepickup' %}</textarea>
```

You should set the rows parameter to the number of lines that the code takes up. The max should be 15 lines. Any longer then that we let the user scroll.

### Punctuation
Only use fullstops when multiple sentances are required. 

Lists should not end in fullstop unless multiple sentences are used.

### Italics
Never use italics instead. Instead you can use either of the following:

```
<em>My subdued text</em>

<span class="subdued">My subdued text</span>
<div class="subdued">My subdued text</div>
<p class="subdued">My subdued text</p>
```
