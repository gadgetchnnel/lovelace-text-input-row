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
      - url: local/path/to/file/lovelace-text-input-row.js?v=0.0.8
        type: js

## Configuration example

    - type: entities
      entities:
        - entity: input_text.announcement_text
          type: 'custom:text-input-row'
        - type: call-service
          name: ' '
          icon: 'mdi:voice'
          action_name: Announce It...
          service: script.send_annoucement

![TextInputRow](https://user-images.githubusercontent.com/2099542/56373939-f9f75e00-61f9-11e9-891e-de790aa5ec62.png)
