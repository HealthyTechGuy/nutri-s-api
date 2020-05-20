# nutri-s-api

### Get Started

```javascript
npm i nutri-s-api
 ```


### Usage

```javascript

const nutriSApi = import 'nutri-s-api'

const apiKey = 'YOUR-API-KEY'
nutriSApi.apiKey(apiKey)




const getNutrients = () => {
	nutriSApi.getNutrients('one avocado').then((res)=> {
		console.log(' res: ', res)
	}).catch((err)=> {
		console.log(' Error: ', err)
	})
}

 ```

