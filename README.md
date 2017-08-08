# facet-panel

A Polymer Element containing a group of facet-lists and date-range-facets.

### Example
```html
<facet-panel
    facets-query="[[facetsQuery]]"
    search-keys="[[searchKeys]]"
    process-request="{{processRequest}}"
    search-endpoint="[[searchEndpoint]]"
    search-fields="[[searchFields]]"
    search-parameters="{{searchParameters}}">
</facet-panel>
```

### Styling

`<facet-panel>` provides the following custom properties and mixins for styling:

Custom property                                 | Description                                  | Default
------------------------------------------------|----------------------------------------------|--------
`--facet-panel-selected-facet-background-color` | The background color of the selected facets. | gray
`--facet-panel-selected-facet-icon-hover-color` | The icon hover color of the selected facets. | white
`--facet-panel-selected-facet-text-color`       | The text color of the selected facets.       | black

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

