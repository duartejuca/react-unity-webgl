# Getting Started

To get started import the default Unity class from react-unity-webgl and include it in your render while giving the public path to your src and loader files.

```js
import React from "react";
import Unity from "react-unity-webgl";

export class App extends React.Component {
  render() {
    return (
      <Unity
        src="Public/Build/myGame.json"
        loader="Public/Build/UnityLoader.js"
      />
    );
  }
}
```
