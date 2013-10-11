A talk by Gustav Kotte from JayWay in Sweden.

* Hypermedia APIs - no app logic in API clients
* Adaptive Web Design - for many devices

Introducing the concept using an HTML app - a Kanban board.

"How much of this is in JavaScript?" Gustav asks.

The API page is just HTML, with links, which can do they same things as the website. No JS, no CSS, just HTML. Easy to test.

He introduces a /profile of his app API, which is built on microformats2 - CSS classnames etc.

Then, he shows a commandline client for the same data.

## Prefer fat APIs over fat clients

Rules: validate that actions taken are correct and will work. A fatter API.

These Rules will have to be in the clients as well - so that they know what they can do at certain times. 

Alas, this duplication is baaaad. 

Better to have the rules in a single place.

## Use HTML for Hypermedia APIs

Ensure that your API data is usable:

Hypermedia constraint: a Jon Moore quote "You do stufff by reading pages, and then either, follow links or submit forms."

* Lots of hypermedia controls.
* Old, standardized everybody knows HTML
* Good tooling support

For instance, a SELECT element is quite cool, has good features as a control.

## Expose semantics using microformats2

Using CSS class names, you can decorate your HTML with extra semantic information.

Your additions to the microformats2 will not be published anywhere, but they can take on the <em>style</em> of that collection of formats.

Presenting denormalized, presentation-friendly FORM elements, with duplicated hidden INPUT fields will make it very easy to consume the forms. They use the data-rel attribute to point to what they mean. For example: "this form moves this Issue to the next Column on the Board".

Primary content: ensure that one piece of content is king on a page. The other pieces can be links, fragment links.

## Hypermedia loves Mobile First

Devices are a challenge - so many of them. Progressive enhancement! 

The API and the HTML can be the same thing!

Same templates!

But: Separate URLs! Segregate, to plan for change later.

This segregation can be optimized, by for instance, not serving JS/CSS for the API perspective.

The Web perspective can drop lots of the additional links.

## Extending Hypermedia apps

Adding a new workflow state to the Kanban Board takes very little code: add a step, and a transition.

Gustav did that real quick.




