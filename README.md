# Documentation for MCPE modal forms


# About Inputs
---
## Input list
+ Button
+ Dropdown
+ Image
+ Input
+ Label
+ Slider
+ StepSlider
+ Toggle

### Button
| Field | Type   |
| ----- | ----   |
| text  | string |
| image | array  |

| image Field | Type   |
| ----------- | ------ |
| type        | string |
| data        | string |

### Dropdown
| Field   | Type   |
| ------- | ------ |
| text    | string |
| default | int    |
| options | array  |

### Image
| Field   | Type   |
| ------- | ------ |
| text    | string |
| texture | string |
| size    | array  |

## Input
| Field       | Type   |
| ----------- | ------ |
| text        | string |
| placeholder | string |
| default     | string |

## Input
| Field       | Type   |
| ----------- | ------ |
| text        | string |
| placeholder | string |
| default     | string |

## Label
| Field       | Type   |
| ----------- | ------ |
| text        | string |

## Slider
| Field   | Type   |
| ------- | ------ |
| text    | string |
| min     | int    |
| max     | int    |
| step    | int    |
| default | int    |

## StepSlider
| Field   | Type   |
| ------- | ------ |
| text    | string |
| steps   | array  |
| default | int    |

## Toggle
| Field   | Type   |
| ------- | ------ |
| text    | string |
| default | int    |

---

# About Packets
---
## Packet list
+ ModalFormRequestPacket
+ ModalFormResponsePacket

## ModalFormRequestPacket
| Field     | Type   |
| --------- | ------ |
| formId    | int    |
| formData  | string |

## ModalFormResponsePacket
| Field     | Type   |
| --------- | ------ |
| formId    | int    |
| formData  | string |
