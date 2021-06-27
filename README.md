# control
I want to think about keyboard layouts and user inputs

## Reasons
- If I am going to learn to become really good with a keyboard layout it should be one that does offer a high maximum efficiency
- I am going to work a lot with that layout, so longterm efficiency is more important than quick learning.
- I like to think about things and want to try some cool things like a dedicated autocomplete button or a side only for macros
- If I switch to a ortholinear keyboard, I need to learn everything again anyway.
- I want to experiment around with creating a modal text editor and a keyboard layout is probably a good starting point

## Keyboard layout
It is probably a good idea to not start completly from scratch, but use some good existing layout as a starting point. These are the criteria

### Criteria for the keyboard layout

- Maximum efficiency is more important than quick learning
- Minimize finger movements / try to keep it at 2-3 keys per finger
- Designed for ortholinear keyboards with thumbcluster only
- Design things to work with muscle memory
- Mainly for programming, so special characters are first class citizens
- Work well with/require a autocomplete function

### Analysis

The required keys are [abcdefghijklmnopqrstuvwxyzA-Z0-9.:,;-_<>()/]
- 52 Letters:
  - ```abcdefghijklmnopqrstuvwxyz```
  - ```ABCDEFGHIJKLMNOPQRSTUVPXYZ```
- 10 Numbers:
  - ```0123456789```
- 24 Special characters
  - ```!"$%&/=?`*+-'#\,;.:-_|@~^```
- 8 Brackets
  - ```()[]{}<>```
- 3 Whitespaces
  - space
  - tab
  - newline
- 2 Control
  - backspace
  - delete
  - nothing else for now
- Modifiers
  - shift
  - program mod1
  - program mod2
  - os mod

## Weird ideas that do not belong here
- The layout switches based on the previous key
- Own keys for things like == != >= &&
