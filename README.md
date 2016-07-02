# weatherapp
weather app which can access city/cities weather data using yahoo external APIs

# Install
1 > Go to the application root.

2 > Run 'npm install'

3 > Run 'node app'

# Consume API

First Method: Dynamic Method

POST : http://localhost:9002/weathers
[  
   {  
      "city":"Delhi"
   },
   {  
      "city":"Gurgaon"
   }
]

OUTPUT:
{
  "Delhi": 27,
  "Gurgaon": 27
}

-----------------------------------------------------------
Second Method: Static - Hardcoded Cities(Delhi, Gurgaon)

GET : http://localhost:9002/weathers

OUTPUT:
{
  "Delhi": 27,
  "Gurgaon": 27
}
