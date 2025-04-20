name: Suggestion
description: 'Request a mod to add compatibility with!'
title: '[Suggestion]: '
assignees:
  - Fyoncle
labels:
  - suggestion
body:
  - type: input
    id: mod_name
    attributes:
      label: Mod Name
      description: What mod should be added for compatibility?
      placeholder: Trinkets
    validations:
      required: true
  - type: textarea
    id: description
    attributes:
      label: Which mobs you want it to be added?
      description: A clear explanation of what GUIs this mod contains that is suitable for GUI Revision Compats.
      placeholder: >-
        This mod adds new GUIs that would look great with GUI Revision.
    validations:
      required: true
