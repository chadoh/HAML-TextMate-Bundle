#HAML TextMate Bundle

##Description

This HAML textmate bundle aids you to code haml even faster

use Cmd+Shift+P to create partial from selection.
This was already implemented in the ruby on rails Bundle, but was explicitly for erb.

##Credits

Created by [Florian Vallen]
Parts of this bundle were ported from the official Ruby Haml TextMate bundle.

##Installation

`git clone...`
`osascript -e 'tell app "TextMate" to reload bundles'`

##Troubleshooting

if you get something like this:
osascript -e 'tell app "TextMate" to reload bundles'
2010-05-10 20:50:41.307 osascript[456:903] Error loading /Library/ScriptingAdditions/Adobe Unit/Contents/MacOS/Adobe Unit Types:  dlopen(/Library/ScriptingAdditions/Adobe Unit/Contents/MacOS/Adobe Unit Types, 262): no suitable image found.  Did find:
/Library/ScriptingAdditions/Adobe Unit/Contents/MacOS/Adobe Unit Types: no matching architecture in universal wrapper
osascript: OpenScripting.framework - scripting addition "/Library/ScriptingAdditions/Adobe Unit" declares no loadable handlers.

try opening the bundle in finder. This did the trick for me.
