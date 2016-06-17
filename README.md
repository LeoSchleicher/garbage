# garbage



* Add these lines to /Applications/Xcode.app/Contents/Frameworks/IDEKit.framework/Resources/IDETextKeyBindingSet.plist
* restart Xcode
* Assign shortcuts to new actions

Code:

    <key>Duplicate Down</key>
    <string>selectLine:, copy:, moveToEndOfLine:, insertNewline:, paste:, deleteBackward:</string>
    <key>Duplicate Up</key>
    <string>selectLine:, copy:, moveUp:, moveToEndOfLine:, insertNewline:, paste:, deleteBackward:</string>
    <key>Delete Line</key>
    <string>deleteToBeginningOfLine:, moveToEndOfLine:, deleteToBeginningOfLine:, deleteBackward:, moveDown:, moveToBeginningOfLine:</string>
