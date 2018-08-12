# Weather Application

Divided the whole application in following components
  - Search Component (Class component)
  - Weather List Component (Class component)
  - Chart (functional component)
  - Google Map (Class component)
  
Search component makes an API request using action and the data is returned in json format.
The latitude/longitude provided in the fetched data is used to create a google map and attach it to a div using ref.
The data fetched such temperature, pressure, humidity are converted to graphs more readable and understandable format using SparkLines from 'react-sparkline'.
The data is completely maintained using redux store.

# Major libraries/packages used
1) axios -> Making http request
2) lodash -> Transform data
3) react, react-dom, react-redux, redux, redux-promise
4) react-sparklines -> For creating charts