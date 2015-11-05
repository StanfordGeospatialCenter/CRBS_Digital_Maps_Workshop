#Code for the Odyssey.js Demo


###Custom Popup HTML Code:

`<div class="cartodb-popup v2">
  <a href="#close" class="cartodb-popup-close-button close">x</a>
  <div class="cartodb-popup-content-wrapper">
    <div class="cartodb-popup-content">
      <img src="{{image_url}}"height="100%" width="100%">
      <h4>name</h4>
      <p>{{name}}</p>
      <h4>year</h4>
      <p>{{year}}</p>
      <h4>address</h4>
      <p>{{address}}</p>
      <h4>neighborhood</h4>
      <p>{{neighborhood}}</p>
      <h4>description</h4>
      <p>{{description}}</p>
      <h4>Image Source</h4>
      <p><a href="{{image_source}}" target=_blank>{{image_source}}</a></p>
      <h4>More info: </h4>
      <p><a href="{{link_url}}" target=_blank>{{link_url}}</a></p>
    </div>
  </div>
  <div class="cartodb-popup-tip-container"></div>
</div>`


###Odyssey.js Markdown



###WTMS Service URL for Basemap

http://georeferencer-0.tileserver.com//3b800fd53ad449f9d89365250b0b42e5385de2a8/map/0E1wB8zfr9TlxahEYadegT/affine/{z}/{x}/{y}.png