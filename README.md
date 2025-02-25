# modal-package

> Npm package to add a react Modal component

## Prerequisites

This project requires React and NPM.
To make sure you have them available on your machine,
try running the following command.

```sh
$ npm -v
```

## Getting Started

These instructions will get you up and running on your local machine.

## Installation

Here is the link of the npm folder: https://www.npmjs.com/package/modal-package?activeTab=readme

Start with adding the package on your local machine:

```sh
$ npm install modal-package
```

## Usage

### Import and setup the package

Import the package:

```sh
$ import { Modal } from 'modal-package';
```

Add the state to control if the modal is visible or not ( Default to false ):

```sh
const [show,setShow] = useState(false);
```

Then add the modal component to the page:

```sh
<Modal title='' onClose={ ()=> setShow(false) } show={show} />
```

### Customization

You can change the content inside the modal by adding a title.
Exemple:

```sh
<Modal title='Employee created' onClose={ ()=> setShow(false) } show={show} />
```

## Author

- **RADHOUANE CHEKKI** - [Github](https://github.com/rc-fe-rc/)
