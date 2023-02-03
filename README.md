# Demo Ember Components

This repo is a plain ember application configured to consume the components in this addon: https://github.com/waynejohnson-karbon/ember-demo-components-addon.

## Configuring locally

In the `ember-demo-components-addon`, use `npm link`. 
In this application, use `npm link ember-demo-components-addon`.

## Running / Development

* `npm start`
* Browse demo container app at [http://localhost:4400](http://localhost:4400).

4400 has been chosen as our app is probably running somewhere in the background, and 4300 is probably used as part of your own experiments. 4400 won't upset other stuff.

### Running Tests

* `ember test`
* `npm test-ui`

Normally you wouldn't write tests for an external addon library, but just to prove that we can.

## Further Reading / Useful Links

* Move all Invoice Presentation/Template Components into a shared Repo: https://dev.azure.com/karbonhq-ops/Karbon%20Product/_workitems/edit/17769