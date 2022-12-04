# chain-icons

A collection of web3 chains/networks SVG icons

Works for any JS framework or vanilla JS as long as you have configured your build system to support importing SVG files - which most of them do out of the box.

## Usage

```js
import polygonSVG from 'chain-icons/svg/polygon.svg';

export default function App() {
	return (
		<div>
			<img src={polygonSVG} alt='Polygon BlockChain' width={200} height={200} />
		</div>
	);
}
```

<br/>

## List of SVGs

Check out the [/svg](./svg) to see the list of available SVGs.

## Source of SVG files

Collection of SVGs are taken from [@thirdweb-dev/chain-icons](https://github.com/thirdweb-dev/chain-icons)
