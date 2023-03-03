<img src="https://ologyyvidss.com/images/logo.png" align="right" style="max-width: 100%"/>

# oLoGYyVidss.com API Wrapper

> oLoGYyVidss provides a simple **HTTP API** to Integrate ours into your Business or Application

## Requirements

-   oLoGYyVidss.com API Key ([Get it here](https://ologyyvidss.com/user/profile/dashboard/edit))
-   npm >=8.3.0
-   node >=16.0.0

## Installation

```bash
npm install ologyyvidss
```
## Usage

```javascript
const oLoGYyVidss = require("ologyyvidss");
const API = new oLoGYyVidss.API("YOUR_API_KEY");

API.searchMovie("Avatar: The Way of Water").then((res) => {
	console.log(res); // Get information on the Movie with the Title Avatar: The Way of Water
});
```
