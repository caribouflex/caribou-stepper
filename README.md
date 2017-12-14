[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/PolymerElements/caribou-timer)

## &lt;caribou-stepper&gt;

`<caribou-stepper>` is a Polymer 2 element used to convey progress through numbered steps (Material Design)

This element allow you to add the quantity of step you want. 
Anything can be inserted into each step.

All the elements can be customized refer to the styling section.

### Incoming (TODO)
- IE11 support
- Horizontal stepper
- Mobile stepper


### Styling
For the styling check the `<caribou-stepper>`, `<caribou-step>` and `<caribou-step-action-buttons>`


## Usage

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="../paper-input/paper-input.html"></script>
    <script src="../iron-icon/iron-icon.html"></script>
    <link rel="import" href="caribou-stepper.html">
    <link rel="import" href="caribou-step.html">
    <style>
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<caribou-stepper linear>
    <caribou-step label="Step 1" open-first-step-on-startup>
       <paper-input always-float-label label="Surname 1"></paper-input>
        <paper-input label="Username 1">
            <iron-icon icon="mail" slot="prefix"></iron-icon>
            <div slot="suffix">@email.com</div>
        </paper-input>
    </caribout-step>
    <caribou-step label="Step 2">
       <paper-input always-float-label label="Surname 2"></paper-input>
        <paper-input label="Username 2">
            <iron-icon icon="mail" slot="prefix"></iron-icon>
            <div slot="suffix">@email.com</div>
        </paper-input>
    </caribout-step>
    <caribou-step label="Step 3">
        <paper-input always-float-label label="Surname 3"></paper-input>
        <paper-input label="Username 3">
            <iron-icon icon="mail" slot="prefix"></iron-icon>
            <div slot="suffix">@email.com</div>
        </paper-input>
    </caribout-step>
</caribou-stepper>
```

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
## Running tests from the command line
When in the caribou-timer directory, run polymer test

## License
Apache License 2.0