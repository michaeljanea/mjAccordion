# mjAccordion
Displays collapsible content panels for presenting information in a limited amount of space.

## How To Install
1. Extract the downloaded zip file (mjAccordion.zip)
2. Insert below codes to the <head> section of your page
`<link rel="stylesheet" type="text/css" href="mjAccordion.css" />`
3. Insert below codes before the </body> tag of your page
```JavaScript
<script type="text/javascript" src="jquery-1.9.1.min.js"></script>
<script type="text/javascript" src="mjAccordion.js"></script>
<script type="text/javascript">
$('.mj_accordion').mjAccordion();
</script>
4. Add the below sample HTML to the BODY of your page
```html
<ul class="mj_accordion">
    <li>
        <div class="mj_accordion_item active">Accordion Item #1</div>
        <div class="mj_accordion_content active">Content 1. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa, suscipit autem sequi perferendis asperiores quidem id sunt officiis molestias nobis. Sint, veritatis, quis voluptates totam sed quod quidem placeat iusto.</div>
    </li>
    
    <li>
        <div class="mj_accordion_item">Accordion Item #2</div>
        <div class="mj_accordion_content">Content 2. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis, nesciunt, accusantium, ad nam officia illum officiis accusamus veniam similique eligendi laborum saepe sed beatae dolores totam suscipit quis corporis qui.</div>
    </li>
    
    <li>
        <div class="mj_accordion_item">Accordion Item #3</div>
        <div class="mj_accordion_content">Content 3. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum, rem, aspernatur iure enim consequatur delectus et nam ratione laboriosam commodi id doloribus dicta odio a nemo numquam consectetur eligendi officia.</div>
    </li>
</ul>
```

## LOGS
##### Version 1.0
Initial release