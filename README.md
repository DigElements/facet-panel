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

Custom property                                 | Description                                                         | Default
------------------------------------------------|---------------------------------------------------------------------|--------
`--facet-panel-bar-color`                       | The color of the single or left bars.                               | --paper-grey-400
`--facet-panel-bar-count-color`                 | The color of the single or left count labels.                       | --paper-grey-900
`--facet-panel-bar-height`                      | The height of the single or left bars.                              | 20px
`--facet-panel-bar-title-color`                 | The color of the single or left title labels.                       | --paper-grey-900
`--facet-panel-bar-title-hover-color`           | The color of the single or left title labels on hover (if a link).  | --paper-grey-700
`--facet-panel-max-height`                      | The max height of the bar chart.                                    | none
`--facet-panel-second-bar-color`                | The color of the right (second) bars.                               | --paper-grey-400
`--facet-panel-second-bar-count-color`          | The color of the right (second) count labels.                       | --paper-grey-900
`--facet-panel-second-bar-height`               | The height of the right (second) bars.                              | 20px
`--facet-panel-second-bar-title-color`          | The color of the right (second) title labels.                       | --paper-grey-900
`--facet-panel-second-bar-title-hover-color`    | The color of the right (second) title labels on hover (if a link).  | --paper-grey-700
`--facet-panel-selected-facet-background-color` | The background color of the selected facets.                        | --paper-grey-400
`--facet-panel-selected-facet-icon-hover-color` | The icon hover color of the selected facets.                        | white
`--facet-panel-selected-facet-text-color`       | The text color of the selected facets.                              | --paper-grey-900

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

