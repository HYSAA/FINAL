﻿FINALS GUIDE
FOR CSS


To use the generator the user has to use
require_once 'CSSGenerator.php';

$filepath-Purpose: Defines the path where the CSS file will be created and saved.

addProperty-Purpose: Adds a CSS property to the current selector.

addCloseSelector-Purpose: Closes the current CSS selector block.

getCSSContent-Purpose: Retrieves the generated CSS content.

////////////////////////////////////////////////////////////////////////////////

FOR HTML
To use the HTML element generator, the user has to include the necessary file:
require_once 'HTMLElementGenerator.php';

Purpose: Instantiate an HTML element of the specified type.

Usage:
$element = new HTMLElement($tagName);

Purpose: Add an attribute to an HTML element.

Usage:
$element->setAttribute($name, $value);

Purpose: Add inner content to an HTML element.

Usage:
$element->setContent($content);

Purpose: Generate the HTML string for the element.

Usage:
$html = $element->render();









