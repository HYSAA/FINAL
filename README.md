FINALS GUIDE
FOR CSS

To use the generator the user has to use
require_once 'CSSGenerator.php';

$filepath-Purpose: Defines the path where the CSS file will be created and saved.

addProperty-Purpose: Adds a CSS property to the current selector.

addCloseSelector-Purpose: Closes the current CSS selector block.

getCSSContent-Purpose: Retrieves the generated CSS content.

////////////////////////////////////////////////////////////////////////////////

FOR HTML

Defined under the namespace MyNamespace

Properties:
html_content:
Private string property that stores the HTML content being generated.

Methods:

addTag($tagName, $attributes = [])
Adds an opening HTML tag with optional attributes.
Parameters:
tagName: String representing the name of the HTML tag (e.g., div, p, span).
attributes: Optional associative array where the key is the attribute name and the value is the attribute value.
Returns:
The instance of the HTMLGenerator class to allow method chaining.

addContent($content)
Adds content inside the current HTML tag.
Parameters:
content: String representing the content to be added inside the HTML tags.
Returns:
The instance of the HTMLGenerator class to allow method chaining.

addCloseTag($tagName)
Adds a closing HTML tag.
Parameters:
tagName: String representing the name of the HTML tag to close (e.g., div, p, span).
Returns:
The instance of the HTMLGenerator class to allow method chaining.

addLinkTag($href, $attributes = [])
Adds a <link> tag with an href attribute and optional additional attributes.

addImgTag($src, $attributes = [])
Adds an <img> tag with a src attribute and optional additional attributes.

getHTMLContent()
Returns the generated HTML content.
