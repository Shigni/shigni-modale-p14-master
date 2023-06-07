# Modale P14
![Modal Screenshot](https://github.com/Shigni/Images/blob/main/Modale%20P14.png)

## Installation
```cmd
npm i shigni-modale-p14-master
```

## Parameters
You'll need to import `useState` from React and set the state first so the modal don't show and is able to reset
```javascript
import React, { useState } from "react";
import Modal from 'shigni-modale-p14-master';

const [displayModal, setDisplayModal] = useState(false);
const [modalReset, setModalReset] = useState(false);
```
you can add a `const` to set css properties to the modal, all listed here
```javascript
const modalParameter = {
	"backgroundColor": "#EEEEEE",   
	"borderRadius": 10,
	"boxShadow": "0 0 5px #1B1919",
	"color": "#1B1919",
	"fontSize": 18,
	"height": "fit-content",
	"padding": "20px 50px",
	"width": "fit-content"
}
```
than add the component to your project, add your function and parameters, you also can change the message,

```javascript
<Modal
          key={modalReset}
          id="modal-created"
          showModal={displayModal}
          closeModal={() => setDisplayModal(false)}
          parameter={modalParameter}
          message="Example"
        />
<<<<<<< HEAD
```
=======
```
>>>>>>> 12c013bda1bfd84c915724182e6060cd6f0235ec
