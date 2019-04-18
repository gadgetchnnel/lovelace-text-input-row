# lovelace-text-input-row
A custom Lovelace text input row for use in entities cards
This will only work for input_text entities.

## Installation

### With custom_updater

    resources:
      - url: /customcards/github/gadgetchnnel/lovelace-text-input-row.js?track=true
        type: js

### Manually

Download the lovelace-text-input-row.js and put it somewhere under *config folder*/www

    resources:
      - url: local/path/to/file/lovelace-text-input-row.js?v=0.0.7
        type: js

## Configuration example

    - type: entities
      entities:
        - entity: input_text.my_text
          type: 'custom:text-input-row'

