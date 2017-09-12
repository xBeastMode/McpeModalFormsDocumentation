# Documentation for MCPE modal forms


# About Inputs

## Input list
+ button
+ dropdown
+ image
+ input
+ label
+ slider
+ step_slider
+ toggle

### button
| Field | Type   |
| ----- | ----   |
| text  | string |
| image | array  |

| image Field | Type   |
| ----------- | ------ |
| type        | string |
| data        | string |

### dropdown
| Field   | Type   |
| ------- | ------ |
| text    | string |
| default | int    |
| options | array  |

### image
| Field   | Type   |
| ------- | ------ |
| text    | string |
| texture | string |
| size    | array  |

### input

| field       | type   |
| ----------- | ------ |
| text        | string |
| placeholder | string |
| default     | string |



### label
| Field       | Type   |
| ----------- | ------ |
| text        | string |

### slider
| Field   | Type   |
| ------- | ------ |
| text    | string |
| min     | int    |
| max     | int    |
| step    | int    |
| default | int    |

### step_slider
| Field   | Type   |
| ------- | ------ |
| text    | string |
| steps   | array  |
| default | int    |

### toggle
| Field   | Type   |
| ------- | ------ |
| text    | string |
| default | int    |



# About Packets

## Packet list
+ ModalFormRequestPacket
+ ModalFormResponsePacket

### ModalFormRequestPacket
| Field     | Type   |
| --------- | ------ |
| formId    | varInt |
| formData  | string |

### ModalFormResponsePacket
| Field     | Type   |
| --------- | ------ |
| formId    | varInt |
| formData  | string |
