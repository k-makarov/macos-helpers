# macos-helpers
mac os little helpers

## Setting colemark keybindings
1. Set Colemark in Preferences -> Keyboard -> Inputs
2. Map Caps key to backspace key:


$ hidutil property --set '{"UserKeyMapping":[{"HIDKeyboardModifierMappingSrc":0x700000039,"HIDKeyboardModifierMappingDst":0x70000002A}]}'
