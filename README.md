# HTML-1
Create a page to add a text input element of "name",
date input, and "birthday"
Javascript will read the date and print out age of user
need the "input" element, which can be give a "type" attribute
of "name" or "date"

Part 2.
Use Javascript to remove images as they are being clicked
DOM commands will be useful here
"node" variable, "node.parentNode" will give you the parent node
Once there's a parent node you can call "parent.removeChild(node)"

Part 3.
Need a Javascript function that will pass an arbitrary DOMNode
needs to traverse the DOM hierarchy upwards, through each successive parent code
until it reaches the top
function needs to return an ordered array of node names (via the "DOMNode.nodeName"property)
that defines the path from the root of the chose node
Path examples: ["document," "body," "div," "img"]
