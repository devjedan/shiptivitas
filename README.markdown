<p align="center">
<a href="https://www.insidesherpa.com/virtual-internships/prototype/oRMogWRHeewqHzA7u/College%20Students%3A%20Learn%20how%20to%20work%20at%20a%20YC%20startup">
<img src="https://s3-ap-southeast-2.amazonaws.com/insidesherpa-assets/yc/yc-blade.png"></a>
<br><br>
  <a href="https://www.insidesherpa.com/virtual-internships/prototype/oRMogWRHeewqHzA7u/College%20Students%3A%20Learn%20how%20to%20work%20at%20a%20YC%20startup">
  <img src="https://s3-ap-southeast-2.amazonaws.com/insidesherpa-assets/yc/workatastartup_logo_orange-c2a27f6374f9395166ee9906e2e0873af835b3c6132ae6aa0543582298567041.svg"></a>
</p>



<h2 id="installation"> Installation </h2>

1. Clone the Shiptivity frontend repository
2. Make the necessary changes to the code (frontend only) and make use of the <a href="#dragula"> Dragula tool </a>

## Available Scripts

In the project directory, you can run:

### `npm start`

this runs the app in the development mode.
<br>Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

We have loaded some clients data in Board.js.
Each client is an object of
interface Client {
  id: number,
  name: string,
  description: string,
  status: 'backlog' | 'in-progress' | 'complete,
}

<p id="dragula">
The Dragula library has been installed, you can use it by importing it on top of each file that you need
<p> 

### `import Dragula from 'dragula';`

then use it by calling `Dragula` directly.

Visit Dragula repository on github for more information
[https://github.com/bevacqua/dragula](https://github.com/bevacqua/dragula)
