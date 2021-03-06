# husk.css

Husk is a simple, lightweight, responsive CSS grid. It's meant to be a solution for newcomers to the CSS world as well as experienced devs seeking simplicity and usability without have to remove unwanted excess.

## Getting Started

Click "Clone or download" to grab a copy of Husk. Copy husk.css into your project foler and create a stylesheet reference to husk.css in the head of your HTML document. 

```
<link rel="stylesheet" type="text/css" href="husk.css">
```

### Important!

It's important to define viewport behaviors (also in the head of your document). Without this, the grid will respond to the browser window resizing but will not respond on actual mobile devices.

```
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
```

### Example Boiler

See index.html for the full boiler. Below are simple HTML grid examples:

```      
<div class="row">
  <div class="container">
    <div class="col-6">
      A div with the col-6 class will take 50% of the row. 
      This of course requires at least one more column in the row.
    </div>
    <div class="col-6">
      Because the columns in each row need to add up to 12. 
      Like many before it, Husk uses a 12 column grid.
    </div>
  </div>
</div> 
    
<div class="row">
  <div class="container">
    <div class="col-12">
      A div with the col-12 class will take 100% of the row. You could have 12 col-1 columns, 
      or any number of combinations per row, so long as the total columns in each row add up to 12.
    </div>
  </div>
</div>
```