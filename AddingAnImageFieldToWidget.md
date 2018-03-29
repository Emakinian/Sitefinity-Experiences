If you want to add an image field to a custom mvc widget, you need to add "sf-html-field" to the components while adding the "sf-image-field".

So your DesignerView.json may look like this:

{
  "priority": 1,
  "components": ["sf-html-field", "sf-image-field", "sf-list-selector" ],
  "scripts": [ ]
}
