Simple PHP Form
===============

Open source automatic PHP form handling module with validation, helpers, warnings and more. Supports text fields, text areas, dropdowns, checkboxes, radio buttons and hidden fields.

Validation flags supported: required, email, phone, number, lengthmax *, lengthmin *, sizemax *, sizemin *

See ./examples/basic.php and ./examples/advanced.php and ./examples/centered.php for usage.

Copyright © Nathaniel Sabanski. Released under the zlib/libpng license.

**SQL for creating the Advanced Example table**

<pre><code> CREATE TABLE `attendees` (
  `id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `realname` varchar(45) NOT NULL,
  `username` varchar(45) NOT NULL,
  `email` varchar(45) NOT NULL,
  `phone` varchar(45) NOT NULL,
  `race` varchar(45) NOT NULL,
  `beverage` int(10) unsigned NOT NULL,
  `suggestions` text NOT NULL,
  `notify` tinyint(1) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8; </code></pre>

**zlib/libpng license**

This software is provided 'as-is', without any express or implied warranty. In no event will the authors be held liable for any damages arising from the use of this software.

Permission is granted to anyone to use this software for any purpose, including commercial applications, and to alter it and redistribute it freely, subject to the following restrictions:

<ul>
<li>The origin of this software must not be misrepresented; you must not claim that you wrote the original software. If you use this software in a product, an acknowledgment in the product documentation would be appreciated but is not required.</li>
<li>Altered source versions must be plainly marked as such, and must not be misrepresented as being the original software.</li>
<li>This notice may not be removed or altered from any source distribution.</li>
</ul>
