# Infostub Instructions

These `.md` should include a table and perhaps a paragraph or two of information. These are then 'included' in other pages, including the region's main page. This allows us to write the infostub once, but have it render multiple times throughout the lorebook. 

The template to reference an infostub so that it renders as if you just repeated the whole table again:
```md
  {<percent_symbol> include-markdown "./stubs/indip_stub.md" <percent_symbol>}
```
(Replace `<percent_symbol>` with `%` when actually referencing an infostub.)