# sortable-lists-with-sortablejs
SortableJS allows your users to reorder items in an unordered lists, giving users a visual dimension to specific actions and modifications

## Tutorial
For detailed instruction's, view Solodev's [How to Create Sortable Lists with SortableJS](https://www.solodev.com/blog/web-design/how-to-create-sortable-lists-with-sortablejs.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/8g4x1nt9/).

## HTML
The tutorial contains the following basic HTML markup.

```
<div class="container">
      <div class="row">
        <div class="col-sm-9 col-xl-10 order-2 order-sm-1 mt-3">
          <h2 class="h6"><strong>Sortable List</strong></h2>
          <div id="sortablelist" class="list-group mb-4 mt-3" data-id="1">
            <div class="list-group-item d-flex align-items-center justify-content-between" data-id="2">
              <div>
                <p class="mb-0 d-inline-flex align-items-center">
                  List Item 1</p>
              </div>
            </div>
            <div class="list-group-item d-flex align-items-center justify-content-between" data-id="3">
              <div>
                <p class="mb-0 d-inline-flex align-items-center">
                  List Item 2</p>
              </div>
            </div>
            <div class="list-group-item d-flex align-items-center justify-content-between" data-id="4" style="">
              <div>
                <p class="mb-0 d-inline-flex align-items-center">
                  List Item 3</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <script>
      new Sortable(sortablelist, {
    animation: 150,
    ghostClass: 'blue-background-class'
});
    </script>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://raw.githack.com/SortableJS/Sortable/master/Sortable.js"></script>
```
