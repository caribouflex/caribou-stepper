[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/caribouflex/caribou-stepper)

## &lt;caribou-stepper&gt;

`<caribou-stepper>` is a Polymer 2 element used to convey progress through numbered steps (Material Design)

This element allow you to add the quantity of step you want. 
Anything can be inserted into each step.

All the elements can be customized refer to the styling section.

### NEW

- Horizontal stepper
- Step validation
- IE11 support
- Step native Required input validation.

### Incoming (TODO)
- GITHUB demo pages.
- Bug Fixes
- Mobile stepper


### Styling
For the styling check the `<caribou-stepper>`, `<caribou-step>` and `<caribou-step-action-buttons>`


## Usage

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
    <link rel="import" href="https://cdn.rawgit.com/download/polymer-cdn/2.3.1/lib/iron-icon/iron-icon.html">
    <link rel="import" href="https://cdn.rawgit.com/download/polymer-cdn/2.3.1/lib/iron-icons/iron-icons.html">
    <link rel="import" href="https://cdn.rawgit.com/download/polymer-cdn/2.3.1/lib/paper-input/paper-input.html">
    <link rel="import" href="caribou-stepper.html">
    <link rel="import" href="caribou-step.html">
    <link rel="import" href="caribou-stepper-custom-icons.html">
    <style>html{font-family: 'Roboto', sans-serif;}</style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<caribou-stepper linear open-first-step-on-startup>
	<caribou-step label="Step 1" open-first-step-on-startup>
  		<paper-input always-float-label label="Surname 1"></paper-input>
      	<paper-input label="Username 1">
        	<iron-icon icon="mail" slot="prefix"></iron-icon>
        	<div slot="suffix">@email.com</div>
      	</paper-input>
  	</caribou-step>
    <caribou-step label="Step 2" open-first-step-on-startup>
  		<paper-input always-float-label label="Surname 2"></paper-input>
      	<paper-input label="Username 2">
        	<iron-icon icon="mail" slot="prefix"></iron-icon>
        	<div slot="suffix">@email.com</div>
      	</paper-input>
  	</caribou-step>
    <caribou-step label="Step 3" open-first-step-on-startup>
  		<paper-input always-float-label label="Surname 3"></paper-input>
      	<paper-input label="Username 3">
        	<iron-icon icon="mail" slot="prefix"></iron-icon>
        	<div slot="suffix">@email.com</div>
      	</paper-input>
  	</caribou-step>
</caribou-stepper>
```

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License
Apache License 2.0

